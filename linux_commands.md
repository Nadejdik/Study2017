# PREMISSIONS 
r(read) w(write) x(execute)
chown(changeFileOwnership) OPTION OWNER FILE
touch(createNewEmptyFile) FILENAME
cp(copyFiles) v(vebouse)i(interactingAskingAPromtBeforeOverwritingFile)
n(doNOToverwriteAlways)r(recursiveIncludeDirectories) SOURCE DESTINATION
dd(utility)OPTIONS OPERAND if=inputFile of=outputFile bs-blockSize count-numOB
mv(moving/renameFiles)-i(interactiveAskAboutRewriting)n(doNotOverwrite)v(vebouse)S D
rm(remove) OPTIONS-rR(deleteDirectory)i9 FILE
rmdir(removeEmptyDirectory)
whoami, uname -asnrvmpio, clear, cal -h, ncal
history !#, !!, !ls
grep(filterSearchInputAndReturnLines)OPTIONS PATTERN [FILE] Ctrl+D
egrep(extendedGrep)
+-oneOrMoreOfPreviousPattern ?- {}-oneOfChar |-logicallOR ()-group
cat OPTION FILENAME
shutdown [OPTIONS] TIME[ MESSAGE](now/hh:mm/+minutes)
date(checkDateTimeOnSystem)
ifconfig(displayNetworkInterfaceConfiguration) OPTIONS
iwconfig(sameAsIfconfigButForWireless)
ps(listProcesses) OPTIONS -e(everyProc)f(moreDetails)
dpkg apt-get search(keyWord)/install(package)/update/upgrade/remove/purge
passwd(updateUserPassword) OPTIONS USER -S(statysInformation USRNAME)
w -husfVo user
which XXX(showsPathToCommand)
type -t
alias name=command
info(s-search,h-help,L-qHelp,HOME&END,[/]-previous/nextNode,u-oneLVLup,q-quit) comm
command —help
locate -c(howManyFiles),b(termInFilename),\(exactlyFilename) (updatebd root user)
find -HLPD PATH EXPRESSION
head
tail -f(viewChanges)
sort(outputSorted) -t(setOtherSeperetor)k(setFiledNumber)n(numeric)r(reverse)
sort -t: -k2 -k1 -k3n filename
wc(provides-l(numberOfLines)w(words)c(bytes)nameOfFile
variableX=“xxx“\export variableX=“xxx“, unset $variableX, variableZ=$variableX` `$variableY


# RegularExpression:
.-anyOneSingleCharacter [range]-anyOneSpecifiedChar [^]-notTheOneSpecChar
*-zeroOrMoreOfChar ^-ifFirstCharThanPatternMustBeAtBeggining $-ifLastCTPMBATheEnd
# Glob characters:
*-zeroOrMoreOfChar ?-anyOneCharacter []-singleChByARangeOfChar !-negatitate 
““-stopInterpretingMetacharAndGlobe '',\-stopInterpretingSpecialChars \-nextCharIsSingleQuoted
``,$()-specifyCommandWithinCommand 
# Control statements: 
;-runMultipleCommandsIndependent &&-runMultipleComDependent ||-runOneOfMultComOR
# MAN:
return/enter-goDownOneLine space-goDOPage /term-searchForTerm n-findNextItem
1G-goToBegin G-goToEnd h-displayHelp q-quitManPage
man -f(section/whatis)k(search/apropos)
