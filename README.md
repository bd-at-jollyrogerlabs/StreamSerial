StreamSerial
============

If you, like me, have a C++ programming background and have gotten
very tired of writing Arduino code like this:

    Serial.print("Here is a number: ");
    Serial.println(aNumber);

and would prefer to write Arduino code like this:

    Serial << "Here is a better way to print this number: " << endl;

then this library is for you.

This has probably been done elsewhere, and may be done better, but
this version is very simple to use, just include StreamSerial.h and
start banging away with operator<< to your heart's content.  Enjoy!
