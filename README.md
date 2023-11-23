<h2>Docker Engine, Jenkins, CI/CD(continuous integration / continuous delivery)</h2>
<h1>Part 1</h1>

![jenkin](https://user-images.githubusercontent.com/98979712/202846748-d56e368d-e30a-441a-9a20-65de1f1f66bc.JPG)
<br>
This lab consists in the first part of Creating and configuring a <code>Jenkins Job</code> of the  <code>free style type</code> and Configuring this Job in order to generate an image (docker build) and publish a <code>docker image</code> of the project on <code>docker hub</code> (Tag latest).<br>
<h1>Part 2</h1>

![jenk3](https://user-images.githubusercontent.com/98979712/202846770-c630c92e-87fa-448e-a2ae-31ea771ed114.JPG)
<br>
In the second part we advance Create another freestyle job containing the same instructions of the previous job of the first part while adding a  <code>Shell script</code> which deploys the image under a new container on <code>docker engine</code>.<br>
<h1>Part 3</h1>
And in the third part we created a job of <code>the pipeline type</code> (which takes up the same tasks of the job previous freestyle but in another way), add without changing anything in the job parameters, a script in the script part of the pipeline ensuring the three internships (Cloning Git, Building image, Publish Image).<br>
<h1>Part 4</h1>
And finally we move on to Create a <code>pipeline type job</code> too. But the latter will contain four Stages (Cloning Git, Building image, Test image, Publish Image) in a <code>'jenkinsfile'</code> file which defines the script ensuring the four stages and subsequently we specified the path of the 'jenkinsfile' file on the job.
