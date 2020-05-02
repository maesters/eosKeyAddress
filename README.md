
**  EOSIO keys and address CLang lib    
**  No dependence except clib. Can be used on linux, windows, Android or iOS    


Makefile is included for a command line example.    
Android NDK .mk files are also tested.   
    
    
void eosPrivate2Address(const char privIn[64], char * privStr, char *addrStr);   

input: privIn - the orignal privKey hex string of 32 bytes. You should produce a good random 256bits number       
output: privStr - EOS privKey WIF format. addrStr - EOS address   
