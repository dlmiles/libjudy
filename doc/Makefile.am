man3_MANS = man/man3/Judy \
	    man/man3/Judy1 \
	    man/man3/Judy1_funcs \
	    man/man3/JudyL \
	    man/man3/JudyL_funcs \
	    man/man3/JudySL \
	    man/man3/JudySL_funcs \
	    man/man3/JudyHS \
	    man/man3/JudyHS_funcs \
	    man/man3/J1T \
	    man/man3/J1S \
	    man/man3/J1U \
	    man/man3/J1F \
	    man/man3/J1N \
	    man/man3/J1L \
	    man/man3/J1P \
	    man/man3/J1FE \
	    man/man3/J1NE \
	    man/man3/J1LE \
	    man/man3/J1PE \
	    man/man3/J1C \
	    man/man3/J1BC \
	    man/man3/J1FA \
	    man/man3/J1MU \
	    man/man3/Judy1Test \
	    man/man3/Judy1Set \
	    man/man3/Judy1Unset \
	    man/man3/Judy1First \
	    man/man3/Judy1Next \
	    man/man3/Judy1Last \
	    man/man3/Judy1Prev \
	    man/man3/Judy1FirstEmpty \
	    man/man3/Judy1NextEmpty \
	    man/man3/Judy1LastEmpty \
	    man/man3/Judy1PrevEmpty \
	    man/man3/Judy1Count \
	    man/man3/Judy1ByCount \
	    man/man3/Judy1FreeArray \
	    man/man3/Judy1MemUsed \
	    man/man3/JudyL \
	    man/man3/JLG \
	    man/man3/JLI \
	    man/man3/JLD \
	    man/man3/JLF \
	    man/man3/JLN \
	    man/man3/JLL \
	    man/man3/JLP \
	    man/man3/JLFE \
	    man/man3/JLNE \
	    man/man3/JLLE \
	    man/man3/JLPE \
	    man/man3/JLC \
	    man/man3/JLBC \
	    man/man3/JLFA \
	    man/man3/JLMU \
	    man/man3/JudyLGet \
	    man/man3/JudyLIns \
	    man/man3/JudyLDel \
	    man/man3/JudyLFirst \
	    man/man3/JudyLNext \
	    man/man3/JudyLLast \
	    man/man3/JudyLPrev \
	    man/man3/JudyLFirstEmpty \
	    man/man3/JudyLNextEmpty \
	    man/man3/JudyLLastEmpty \
	    man/man3/JudyLPrevEmpty \
	    man/man3/JudyLCount \
	    man/man3/JudyLByCount \
	    man/man3/JudyLFreeArray \
	    man/man3/JudyLMemUsed \
	    man/man3/JSLG \
	    man/man3/JSLI \
	    man/man3/JSLD \
	    man/man3/JSLF \
	    man/man3/JSLN \
	    man/man3/JSLL \
	    man/man3/JSLP \
	    man/man3/JSLFA \
	    man/man3/JudySLGet \
	    man/man3/JudySLIns \
	    man/man3/JudySLDel \
	    man/man3/JudySLFirst \
	    man/man3/JudySLNext \
	    man/man3/JudySLLast \
	    man/man3/JudySLPrev \
	    man/man3/JudySLFreeArray \
	    man/man3/JHSG \
	    man/man3/JHSI \
	    man/man3/JHSD \
	    man/man3/JHSFA \
	    man/man3/JudyHSGet \
	    man/man3/JudyHSIns \
	    man/man3/JudyHSDel \
	    man/man3/JudyHSFreeArray


man/man3:
	test -d "man/man3" || mkdir -p "man/man3"


man/man3/Judy: | man/man3
	../tool/jhton @srcdir@/ext/Judy_3.htm | grep -v '^[   ]*$$' | sed -e 's/\.C//' >  man/man3/Judy


man/man3/Judy1: | man/man3
	../tool/jhton @srcdir@/ext/Judy1_3.htm | grep -v '^[   ]*$$' | sed -e 's/\.C//' > man/man3/Judy1

man/man3/J1T \
man/man3/J1S \
man/man3/J1U \
man/man3/J1F \
man/man3/J1N \
man/man3/J1L \
man/man3/J1P \
man/man3/J1FE \
man/man3/J1NE \
man/man3/J1LE \
man/man3/J1PE \
man/man3/J1C \
man/man3/J1BC \
man/man3/J1FA \
man/man3/J1MU: man/man3/Judy1
	test -e $@ || ln -s Judy1 $@


man/man3/Judy1_funcs: | man/man3
	../tool/jhton @srcdir@/ext/Judy1_funcs_3.htm | grep -v '^[   ]*$$' | sed -e 's/\.C//' > man/man3/Judy1_funcs

man/man3/Judy1Test  \
man/man3/Judy1Set  \
man/man3/Judy1Unset  \
man/man3/Judy1First  \
man/man3/Judy1Next \
man/man3/Judy1Last \
man/man3/Judy1Prev \
man/man3/Judy1FirstEmpty \
man/man3/Judy1NextEmpty \
man/man3/Judy1LastEmpty \
man/man3/Judy1PrevEmpty \
man/man3/Judy1Count \
man/man3/Judy1ByCount \
man/man3/Judy1FreeArray \
man/man3/Judy1MemUsed: man/man3/Judy1_funcs
	test -e $@ || ln -s Judy1_funcs $@


man/man3/JudyL: | man/man3
	../tool/jhton @srcdir@/ext/JudyL_3.htm | grep -v '^[   ]*$$' | sed -e 's/\.C//' > man/man3/JudyL

man/man3/JLG \
man/man3/JLI \
man/man3/JLD \
man/man3/JLF \
man/man3/JLN \
man/man3/JLL \
man/man3/JLP \
man/man3/JLFE \
man/man3/JLNE \
man/man3/JLLE \
man/man3/JLPE \
man/man3/JLC \
man/man3/JLBC \
man/man3/JLFA \
man/man3/JLMU: man/man3/JudyL
	test -e $@ || ln -s JudyL $@


man/man3/JudyL_funcs: | man/man3
	../tool/jhton @srcdir@/ext/JudyL_funcs_3.htm | grep -v '^[   ]*$$' | sed -e 's/\.C//' > man/man3/JudyL_funcs

man/man3/JudyLGet \
man/man3/JudyLIns \
man/man3/JudyLDel \
man/man3/JudyLFirst \
man/man3/JudyLNext \
man/man3/JudyLLast \
man/man3/JudyLPrev \
man/man3/JudyLFirstEmpty \
man/man3/JudyLNextEmpty \
man/man3/JudyLLastEmpty \
man/man3/JudyLPrevEmpty \
man/man3/JudyLCount \
man/man3/JudyLByCount \
man/man3/JudyLFreeArray \
man/man3/JudyLMemUsed: man/man3/JudyL_funcs
	test -e $@ || ln -s JudyL_funcs $@


man/man3/JudySL: | man/man3
	../tool/jhton @srcdir@/ext/JudySL_3.htm | grep -v '^[   ]*$$' | sed -e 's/\.C//' > man/man3/JudySL

man/man3/JSLG \
man/man3/JSLI \
man/man3/JSLD \
man/man3/JSLF \
man/man3/JSLN \
man/man3/JSLL \
man/man3/JSLP \
man/man3/JSLFA: man/man3/JudySL
	test -e $@ || ln -s JudySL $@


man/man3/JudySL_funcs: | man/man3
	../tool/jhton @srcdir@/ext/JudySL_funcs_3.htm | grep -v '^[   ]*$$' | sed -e 's/\.C//' > man/man3/JudySL_funcs

man/man3/JudySLGet \
man/man3/JudySLIns \
man/man3/JudySLDel \
man/man3/JudySLFirst \
man/man3/JudySLNext \
man/man3/JudySLLast \
man/man3/JudySLPrev \
man/man3/JudySLFreeArray: man/man3/JudySL_funcs
	test -e $@ || ln -s JudySL_funcs $@


man/man3/JudyHS: | man/man3
	../tool/jhton @srcdir@/ext/JudyHS_3.htm | grep -v '^[   ]*$$' | sed -e 's/\.C//' > man/man3/JudyHS

man/man3/JHSG  \
man/man3/JHSI \
man/man3/JHSD \
man/man3/JHSFA: man/man3/JudyHS
	test -e $@ || ln -s JudyHS $@


man/man3/JudyHS_funcs: | man/man3
	../tool/jhton @srcdir@/ext/JudyHS_funcs_3.htm | grep -v '^[   ]*$$' | sed -e 's/\.C//' > man/man3/JudyHS_funcs

man/man3/JudyHSGet \
man/man3/JudyHSIns \
man/man3/JudyHSDel \
man/man3/JudyHSFreeArray: man/man3/JudyHS_funcs
	test -e $@ || ln -s JudyHS_funcs $@

CLEANFILES = man/man3/*
