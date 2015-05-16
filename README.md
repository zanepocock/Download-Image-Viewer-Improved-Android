# Download-Image-Viewer-Improved-Android
Second assignment for second Android POSA15 MOOC

As per course description:

The purpose of this assignment is to give you experience using Android Services by developing an app containing a main Activity that prompts the user for URLs of images to download concurrently via a DownloadImagesService and then view via a DisplayImagesActivity. DownloadImagesService is implemented via an Android <a href="http://developer.android.com/guide/components/bound-services.html">Bound Service</a>, as covered in <a href="https://www.youtube.com/watch?v=yMaTUNVdeBI&index=36&list=PLZ9NgFYEMxp4tbiFYip6tDNIEBRUDyPQK">this video</a>, and several instances of the Android <a href="http://developer.android.com/reference/android/os/Messenger.html">Messenger</a> class, which is covered in the following videos:

  <ul>
    <li> <a href="https://www.youtube.com/watch?v=Bfu14K74DxQ&index=41&list=PLZ9NgFYEMxp4tbiFYip6tDNIEBRUDyPQK">Service to Activity Communication via Android Messenger</a>.</li>
    <li> <a href="https://www.youtube.com/watch?v=rGH0U_p1pow&index=42&list=PLZ9NgFYEMxp4tbiFYip6tDNIEBRUDyPQK">Programming Bound Services with Messengers (Part 1)</a>.</li>
    <li> <a href="https://www.youtube.com/watch?v=cRFw7xaZ_Mg&index=43&list=PLZ9NgFYEMxp4tbiFYip6tDNIEBRUDyPQK">Programming Bound Services with Messengers (Part 2)</a>.</li>
  </ul>

In addition, the RequestHandler (which is associated with the DownloadImagesBoundService) will use an Java ExecutorService to concurrently download images and send their URIs back to the Activity. The Java ExecutorService is covered in <a href="https://www.youtube.com/watch?v=2NAlvSkK9-k&index=27&list=PLZ9NgFYEMxp4KSJPUyaQCj7x--NQ6kvcX">this</a> video. Material presented during lectures in Weeks 2 of the class are also relevant to this assignment.

#Skeleton Code

Skeleton code for this assignment is available <a href="https://github.com/douglascraigschmidt/POSA-15/tree/master/assignments/assignment2">here</a>. Pull the appropriate skeleton code into your repository, read it carefully, and complete the "TODO" markers, which reside in the following Java source files: DownloadImagesBoundService.java, ImageOpsBoundService.java, RequestHandler.java, ReplyMessage.java, and RequestMessage.java.

Note that there are no automated unit tests for this assignment. Instead, you'll know the program is working when you can successfully download and view an image.  However, make sure your program works for both valid and invalid URL input.

#Concluding Remarks

This assignment is designed to further your understanding with programming Android Services in Java.  It's harder than the first assignment since you'll need to write some code on the client-side, as well as code to perform concurrent background processing with an Android Bound Service on the server-side. Therefore, start early and come to Virtual Office Hours if you have questions or run into problems.  </p>
