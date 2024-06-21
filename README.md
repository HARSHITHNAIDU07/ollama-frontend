install ollama 
    use the following command for linux :
    
      curl -fsSL https://ollama.com/install.sh | sh
      
   u could download ollama form website for windows and mac

install llama3 on ollama with the help of the following command

    ollama run llama3

create the custom model on llama3 baseline

    ollama create rinlbot -f ./modelfile.txt
  
  (NOTE: all these commands must be run on the folder that's forked from the file)

install angular,node js for frontend

configure the ip adress in appconfig.ts present in src/components/app to the ip adress of the ollama server


to run thisuse the following commands

    ollama serve

 note: if you encounter by "Error: listen tcp 127.0.0.1:11434 bind: Only one usage of each socket address (protocol/network address/port) is normally permitted. the run the following command
 
    set OLLAMA_HOST=0.0.0.0
if you get this everytime then create a local variable for OLLAMA_HOST and set it to 0.0.0.0

then hit

    
    npm start

after successfully running these commands u could view the chat bot at localhost:4200
