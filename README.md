If you don't understand this code: 
ls:[];bm:(#flat({"+-<>[].,"?x}'input`))#0;pc:0;t:,0;tp:0
i:0;{:[x=4;ls,:i;x=5;:{m::*ls#-1;ls_:-1;bm@:m,i;bm@:i,m}];i+:1}'p
do({pc<#p};{(({t@:(succ t tp),tp},{t@:(pred t tp),tp},{tp-:1},{tp+:1;:[tp=#t;t,:0]},{:[0=t tp;pc:bm pc]},{:[~0=t tp;pc:bm pc]},{say(?t tp)},{t@:(#getc()),tp})@p pc)();pc+:1});"\n"

... I have nothing to talk with you.
