# Real_Time_DSP-Codes
Contains codes used for implementation of signal processing algorithm on smart phone.

Steps to create APK.

1. Write MATLAB code for any algorithm (in this case DSP), Test it in MATLAB environment for correctness.
2. Use MathCoder tool, to Convert MATLAB to C language. (Wow, This is awesome. No head banging for variable declaration and pointers :P)
3. Copy all the files generated from MathCoder.
4. Create a Project In android Studio
5. Use JNI inerface and add files generated by Mathcoder to JNI folder.
6. Create GUI to input user choice of parmeters. (Be creative in GUI)
7. Build and generate APK.
8. Use it on phone, and SHOW OFF !!

Thanks to Dr. Kehtarnavaz University Of Texas At Dallas, who taught this course. Using Mobile phone as platform, we can run any complex algorithm in hand and in REAL TIME. Feel Free to read the book " Smartphone-Based Real-Time Digital Signal Processing"
