jshell> void Calculator(int i, int a) {
	...> System.out.printf("%d + %d=%d", i, a, i+a) .println();
	...> System.out.printf("%d - %d=%d", i, a, i-a) .println();
	...> System.out.printf("%d * %d=%d", i, a, i*a) .println();	
	...> System.out.printf("%d / %d=%d", i, a, i/a) .println();
	...> System.out.printf("%d % %d=%d", i, a, i%a) .println();
   ...> }
created method Calculator(int,int)

jshell> Calculator(992,9)
992 + 8=1000
992 - 8=984
992 * 8=7936
992 / 8=124
   java.util.illegalFormatFlagException thrown: Flags =' '
	at Formatter$FormatSpecifier.checkText (Formatter.java:3094)
	at Formatter$FormatSpecifer.<init> (Formatter.java:2786)
	at Formatter.parse (Formatter.java:2621)
	at Formatter.format (Formatter.java:2563)
	at PrintStream.format (PrintStreem.java:974)
	at PrintStream.print  (PrintStreem.java:870)
	at Calculator (1:6)
	at (#2:1)

jshell>
