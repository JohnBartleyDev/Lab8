all images are in the screenshot folder



checkpoint 2:

1.You can see what test were run for a particular submission by clicking on the build name, scrolling to the bottom of the build page, and then clicking on test summary

2.one submission with an error is the cmake-windows\_vs2022\_x64\_ninja build, which fails the [CMake.WriteCompilerDetecRuntionHeader ](https://open.cdash.org/testSummary.php?project=1&name=RunCMake.WriteCompilerDetectionHeader&date=2022-07-25)test. this helps us debug the failure as it allows us to read the failed debug log for the test.

3.My system is similar to the WindowsServer2016-VS2017-64-CUDA11.0.221 build, which has an incredibly clean dashboard of 0 errors, warnings



For my submission there were no errors



checkpoint 3.


-the information provided shows you which test failed a check and the -W command shows you all the checks of each test



