#Erklärung der Problemlösung

zuerst habe ich mir mit "git diff" den Unterschied angesehen und festgestellt dass beide Versionen nicht 
"Moin Moin" ausgeben. Ich habe dann die Java Datein so umgeändert dass sie "Moin Moin" ausgibt, sie per git add dem index hinzugefügt und mit git commit committed, danach wurden meine branches gemergt.

#Mir ist aufgefallen dass wir erklären sollten wie man die Datei Kompilliert und ausführt

Man Kompilliert sie mit dem javac befehl und dem Namen, also: javac HelloWorld.java.
Ausführen tut man dann die neue class file mit java HelloWorld.class