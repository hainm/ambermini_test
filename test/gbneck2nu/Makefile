test:
	-cd 1hji && ./Run.1hji_md
	-cd modified_nu/3p4a/ && ./Run.3p4a
	-export TESTsander='../../../bin/pmemd'; cd 1hji && ./Run.1hji_md
	-export TESTsander='../../../../bin/pmemd'; cd modified_nu/3p4a/ && ./Run.3p4a 

test.sander:
	-cd 1hji && ./Run.1hji_md
	-cd modified_nu/3p4a/ && ./Run.3p4a

test.pmemd:
	-export TESTsander='../../../bin/pmemd'; cd 1hji && ./Run.1hji_md
	-export TESTsander='../../../../bin/pmemd'; cd modified_nu/3p4a/ && ./Run.3p4a 

test.cuda:
	-export TESTsander='../../../bin/pmemd.cuda'; cd 1hji && ./Run.1hji_md
	-export TESTsander='../../../../bin/pmemd.cuda'; cd modified_nu/3p4a/ && ./Run.3p4a 
