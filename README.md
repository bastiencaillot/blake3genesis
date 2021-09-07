# blake3genesis🦄
A python script for creating the parameters required for a unique genesis block with blake3 hash function

      git clone https://github.com/bastiencaillot/blake3genesis
      
      cd blake3genesis

You will need to install Blake3 dependencies in python, for example with the following code (on Ubuntu):

               sudo apt install python3-pip
               pip3 install blake3
               pip3 install construct==2.5.2
               
               
               
 Then, run : 
           
            python3 genesis.py
            
You can change the timestamp for example,

based on https://github.com/lhartikk/GenesisH0/ source code, and thanks to the efokschaner source code which enabled me to switch to Python 3 and use Blake3
