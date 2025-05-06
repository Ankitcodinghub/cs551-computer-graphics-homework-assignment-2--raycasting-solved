# cs551-computer-graphics-homework-assignment-2--raycasting-solved
**TO GET THIS SOLUTION VISIT:** [CS551 Computer Graphics Homework Assignment 2 -Raycasting Solved](https://www.ankitcodinghub.com/product/cs551-computer-graphics-homework-assignment-2-raycasting-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96970&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS551 Computer Graphics Homework Assignment 2 -Raycasting Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<h2 dir="auto">Overview:</h2>
<p dir="auto">In this assignment, you will be implementing a raycaster, which is the first step to creating a raytracer. You will be able to create stunning artwork like this:

<p dir="auto"><a href="https://i0.wp.com/github.com/yig/graphics101-raycasting/blob/master/docs/readme_images/spheres_cylinder.png?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-raycasting/raw/master/docs/readme_images/spheres_cylinder.png?w=980&amp;ssl=1" alt="solid color spheres and a cylinder" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>

<p dir="auto">The assignment is broken down into three parts: (1) creating 3D rays through pixels, (2) intersecting 3D rays with various 3D shapes, and (3) computing a color for the ray.

<p dir="auto">(You will add illumination in the follow-up assignment,&nbsp;<a href="https://github.com/yig/graphics101-raytracing">raytracing</a>.)

<h2 dir="auto">Goals:</h2>
<ul dir="auto">
<li>
<p dir="auto">Understand how to create a virtual picture of a 3D scene.

</li>
<li>
<p dir="auto">Gain experience deriving and implementing mathematical expressions for geometric calculations.

</li>
<li>
<p dir="auto">Become familiar with a 3D math library (bonus: identical to one available when programming for a GPU).

</li>
<li>
<p dir="auto">Become more comfortable with C++.

</li>
</ul>
<h2 dir="auto">Background:</h2>
<ul dir="auto">
<li>Book (FoCG,4e): Chapter 4&nbsp;<em>Ray Tracing</em>&nbsp;and Chapter 13.2&nbsp;<em>Instancing</em>.</li>
<li>Video: “Lecture 3: Transformations”, “Lecture 4: Raycasting”, and “Assignment 2: Raycasting”</li>
<li>Quiz: Transformations, Raycasting</li>
</ul>
<p dir="auto">(FoCG,4e is&nbsp;<em>Fundamentals of Computer Graphics (4th edition)</em>&nbsp;by Steve Marschner and Peter Shirley.)

<h2 dir="auto">Getting Started &amp; Handing In:</h2>
<ul dir="auto">
<li>
<p dir="auto">Download or clone this code repository. Don’t fork it on GitHub, or else your code will be visible to everyone.

</li>
<li>
<p dir="auto">Follow the instructions to install a working development environment:&nbsp;<a href="https://github.com/yig/graphics101">https://github.com/yig/graphics101</a>&nbsp;. You do not need to install Qt or any other external libraries for this assignment.

</li>
<li>
<p dir="auto">The program is a command line program. The framework and included&nbsp;<code>glm</code>&nbsp;vector math library provide all the support code that you need.

</li>
<li>
<p dir="auto">The code will be written in C++. This time, the project is more complex and you will see and need to use more of the language, including the&nbsp;<code>std::vector</code>&nbsp;container class and object-oriented programming. I have made use of the modern C++11 standard where appropriate. This makes the language easier to write and safer, though some reference material, tutorials, and examples you find will be outdated.

</li>
<li>
<p dir="auto">Build and run the code. The code should compile, but it will complain when running about not having enough arguments. You should see a message like:

<div class="snippet-clipboard-content notranslate position-relative overflow-auto">
<pre class="notranslate"><code>  Usage: raycasting path/to/scene.json image_out.png long_edge_pixels
</code></pre>
</div>
</li>
<li>
<p dir="auto">If you are using an IDE like Qt Creator, you will need to set the command line arguments used when running your program. In Qt Creator, click on “Projects” and then, under “Build &amp; Run”, click on “Run.” Set the “Command line arguments” appropriately. For example:

<div class="snippet-clipboard-content notranslate position-relative overflow-auto">
<pre class="notranslate"><code>  spheres_cylinder.json spheres_cylinder-test.png 500
</code></pre>
</div>
<p dir="auto"><a href="https://i0.wp.com/github.com/yig/graphics101-raycasting/blob/master/docs/readme_images/qt-creator.png?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" style="box-sizing: content-box; border-style: none; max-width: 100%; background-color: var(--color-canvas-default);" data-src="https://i0.wp.com/github.com/yig/graphics101-raycasting/raw/master/docs/readme_images/qt-creator.png?w=980&amp;ssl=1" alt="Qt Creator > Projects > Run > Command Line Arguments" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>

<p dir="auto">For those arguments to work, you would either need to set “Working directory” to the&nbsp;<code>examples</code>&nbsp;subdirectory, or else copy&nbsp;<code>spheres_cylinder.json</code>&nbsp;next to the “Executable” (or wherever you point “Working directory”).

</li>
<li>
<p dir="auto">Add your code to&nbsp;<code>camera.cpp</code>,&nbsp;<code>scene.cpp</code>, and&nbsp;<code>shape.cpp</code>.

</li>
<li>
<p dir="auto">Build and run and test that it is working correctly. Qt Creator has a great debugger interface.

</li>
<li>
<p dir="auto">Check your work with the command line tests by running&nbsp;<code>ctest --verbose</code>. This will test whether your Camera and Scene classes are working correctly. If your Camera and Scene classes are not working correctly, nothing will render correctly for the autograder.

</li>
<li>
<p dir="auto">Check your work with the&nbsp;<a href="https://github.com/yig/graphics101-raycasting-autograder">autograder</a>.

</li>
<li>
<p dir="auto">Copy the latest autograder output (<code>.html</code>&nbsp;file and associated directory) into a new&nbsp;<code>output/</code>&nbsp;subdirectory.

</li>
<li>
<p dir="auto">Create a&nbsp;<code>.json</code>&nbsp;scene yourself. Copy it and a&nbsp;<code>.png</code>&nbsp;rendering of it into the&nbsp;<code>output/</code>&nbsp;subdirectory as well.

</li>
<li>
<p dir="auto">You are encouraged to share blooper images you create while implementing the assignment on Piazza.

</li>
<li>
<p dir="auto">Create a file named&nbsp;<code>Notes.txt</code>&nbsp;in the folder. Describe any known issues or extra features. Name people in the class who deserve a star for helping you (not by giving your their code!).

</li>
<li>
<p dir="auto">When done, run the the&nbsp;<code>cpack</code>&nbsp;command from inside your build directory to generate an appropriate zip file of your&nbsp;<code>raycasting</code>&nbsp;project. The zip file it creates,&nbsp;<code>raycasting.zip</code>, will include the&nbsp;<code>output</code>&nbsp;subdirectory and your&nbsp;<code>Notes.txt</code>&nbsp;file. It will ignore unneeded large and numerous directories (e.g.,&nbsp;<code>build</code>&nbsp;and&nbsp;<code>include</code>). Upload your&nbsp;<code>raycasting.zip</code>&nbsp;before the deadline.&nbsp;<strong>If you try to upload a zip file with too many files in it, Gradescope will return error code 0.</strong>&nbsp;(If you can’t use&nbsp;<code>cpack</code>, try&nbsp;<code>make zip</code>&nbsp;or&nbsp;<code>cmake --build . --target zip</code>) If you create a zip file manually, zip your project without the&nbsp;<code>build</code>&nbsp;directory.

</li>
<li>
<p dir="auto"><strong>THIS IS AN INDIVIDUAL, NOT A GROUP ASSIGNMENT. That means all code written for this assignment should be original! Although you are permitted to consult with each other while working on this assignment, code that is substantially the same will be considered cheating.</strong>

</li>
</ul>
<h2 dir="auto">Rubric</h2>
<ul dir="auto">
<li>
<p dir="auto"><strong>(10 points)</strong>&nbsp;3D rays through pixels. The&nbsp;<code>Camera</code>&nbsp;methods:

<ul dir="auto">
<li>
<p dir="auto"><strong>(5 points)</strong>&nbsp;<code>CameraPerspective::getRay( u,v )</code>

<ul dir="auto">
<li>Return a world-space ray through the pixel located at (<em>u,v</em>) on the film plane. A point (<em>u,v</em>) on the film plane is located at&nbsp;<strong>e</strong>&nbsp;+&nbsp;<em>u</em>&nbsp;<strong>u</strong>&nbsp;+&nbsp;<em>v</em>&nbsp;<strong>v</strong>&nbsp;–&nbsp;<em>d</em>&nbsp;<strong>w</strong>&nbsp;in world-space. Your ray should emanate from the eye&nbsp;<strong>e</strong>&nbsp;itself. The world-space direction of the ray is the direction from the eye&nbsp;<strong>e</strong>&nbsp;through the aforementioned film plane point:&nbsp;<em>u</em>&nbsp;<strong>u</strong>&nbsp;+&nbsp;<em>v</em>&nbsp;<strong>v</strong>&nbsp;–&nbsp;<em>d</em>&nbsp;<strong>w</strong>.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(5 points)</strong>&nbsp;<code>CameraOrthographic::getRay( u,v )</code>

<ul dir="auto">
<li>Return a world-space ray through the pixel located at (<em>u,v</em>) on the film plane. A point (<em>u,v</em>) on the film plane is located at&nbsp;<strong>e</strong>&nbsp;+&nbsp;<em>u</em>&nbsp;<strong>u</strong>&nbsp;+&nbsp;<em>v</em>&nbsp;<strong>v</strong>&nbsp;in world-space. The world-space rays of an orthographic camera are all parallel, in the direction –<strong>w</strong>.</li>
</ul>
</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(10 points)</strong>&nbsp;The rendering loop.&nbsp;<code>Scene</code>&nbsp;methods:

<ul dir="auto">
<li>
<p dir="auto"><strong>(4 points)</strong>&nbsp;<code>render()</code>

<ul dir="auto">
<li>Converts a pixel’s x,y coordinates to u,v coordinates via&nbsp;<code>camera-&gt;getPixelUV()</code>&nbsp;and then to a world-space ray via&nbsp;<code>camera-&gt;getRay()</code>. Then, get the light along the ray by calling&nbsp;<code>rayColor()</code>.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(1 point)</strong>&nbsp;<code>rayColor()</code>

<ul dir="auto">
<li>Returns the light along the given ray as a color. In this raycasting assignment,&nbsp;<code>rayColor()</code>&nbsp;will call&nbsp;<code>closestIntersection()</code>&nbsp;and return the color of the closest intersected object.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(5 points)</strong>&nbsp;<code>closestIntersection()</code>

<ul dir="auto">
<li>Calls&nbsp;<code>rayIntersect()</code>&nbsp;on every shape and returns the closest one (smallest&nbsp;<em>t</em>).</li>
</ul>
</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(75 points)</strong>&nbsp;Intersections. The&nbsp;<code>Shape</code>&nbsp;subclasses’&nbsp;<code>rayIntersect()</code>&nbsp;methods:

<ul dir="auto">
<li>
<p dir="auto"><strong>(15 points)</strong>&nbsp;Plane (the&nbsp;<em>xy</em>&nbsp;plane, also known as the&nbsp;<em>z</em>&nbsp;= 0 plane)

<ul dir="auto">
<li>F(x,y,z) = z</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(15 points)</strong>&nbsp;Sphere (centered at the origin with radius 1):

<ul dir="auto">
<li>F(x,y,z) = x² + y² + z² – 1</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(15 points)</strong>&nbsp;Cylinder (bottom at the origin, top at (0,0,1), radius 1) with a top and bottom cap (circles with radius 1 at z=0 and z=1). You handle this as a collection of three shapes with conditions:

<ul dir="auto">
<li>if 0 &lt; z &lt; 1: F(x,y,z) = x² + y² – 1</li>
<li>if x² + y² &lt; 1: F(x,y,z) = -z</li>
<li>if x² + y² &lt; 1: F(x,y,z) = z-1</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(15 points)</strong>&nbsp;Cone (bottom at the origin, top at (0,0,1), radius 1 at the bottom, radius 0 at the top, with a bottom cap). You handle this as a collection of two shapes with conditions:

<ul dir="auto">
<li>if 0 &lt; z ≤ 1: F(x,y,z) = x² + y² – (1 – z)²</li>
<li>if x² + y² &lt; 1: F(x,y,z) = -z</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(15 points)</strong>&nbsp;Cube (centered at the origin, with vertices ( ±1, ±1, ±1)). Think of it as six planes:

<ul dir="auto">
<li>if -1 ≤ y,z ≤ 1: F(x,y,z) = x-1</li>
<li>if -1 ≤ y,z ≤ 1: F(x,y,z) = -(x+1)</li>
<li>if -1 ≤ x,z ≤ 1: F(x,y,z) = y-1</li>
<li>if -1 ≤ x,z ≤ 1: F(x,y,z) = -(y+1)</li>
<li>if -1 ≤ x,y ≤ 1: F(x,y,z) = z-1</li>
<li>if -1 ≤ x,y ≤ 1: F(x,y,z) = -(z+1)</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(bonus 25 points)</strong>&nbsp;Mesh (arbitrary triangle meshes)

<ul dir="auto">
<li>
<p dir="auto">Intersect with all triangles of the mesh. None of the demo scene files use this, so you’ll have to create your own. The&nbsp;<code>Mesh</code>&nbsp;class stores a triangle mesh. A triangle has three corners. At each corner there is a position and possibly also a normal and texture coordinate. So there are three corresponding arrays,&nbsp;<code>face_positions</code>,&nbsp;<code>face_normals</code>, and&nbsp;<code>face_texcoords</code>. (If the mesh has normals or texture coordinates, then&nbsp;<code>face_normals</code>&nbsp;or&nbsp;<code>face_texcoords</code>&nbsp;will be the same length as&nbsp;<code>face_positions</code>. If it doesn’t, their length will be 0.) Each element in these arrays stores three integer indices, one for each corner of the triangle. The indices tell you where to look in the&nbsp;<code>positions</code>,&nbsp;<code>normals</code>, and&nbsp;<code>texcoords</code>&nbsp;arrays for the 3D position, 3D normal, and 2D texture coordinates at that corner. Putting this all together, you can access the 3D positions for the three corners of the&nbsp;<code>i</code>-th triangle like this:

<div class="snippet-clipboard-content notranslate position-relative overflow-auto">
<pre class="notranslate"><code>  const vec3 p0 = positions[face_positions[i][0]];
  const vec3 p1 = positions[face_positions[i][1]];
  const vec3 p2 = positions[face_positions[i][2]];
</code></pre>
</div>
</li>
</ul>
</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(5 points)</strong>&nbsp;An example scene file. Note that&nbsp;<code>defaults.json</code>&nbsp;is not a real example, it just contains sample parameters (matching what the objects’ constructors would set) or sample parameters (for the transforms). Also note that if a transform dictionary contains a&nbsp;<code>translate</code>,&nbsp;<code>rotate</code>,&nbsp;<code>scale</code>, and&nbsp;<code>matrix</code>, they will be applied to the object in the order:&nbsp;<code>matrix * translate * rotate * scale</code>.

</li>
</ul>
<h2 dir="auto">The code</h2>
<p dir="auto">The code for a raycaster/raytracer can actually be quite compact. Here is a walkthrough. When the program launches (<code>main.cpp</code>), the&nbsp;<code>main()</code>&nbsp;function creates a&nbsp;<code>Scene</code>&nbsp;object. The scene parses the&nbsp;<code>.json</code>&nbsp;input file (<code>parser.cpp</code>). The&nbsp;<code>main()</code>&nbsp;function then creates an&nbsp;<code>Image</code>&nbsp;to store the rendering result, and passes it to&nbsp;<code>scene.render()</code>. The code for&nbsp;<code>Scene::render()</code>&nbsp;is in&nbsp;<code>scene.cpp</code>. You will fill in&nbsp;<code>Scene::render()</code>&nbsp;and its helper methods:

<ul dir="auto">
<li>
<p dir="auto"><code>CameraPerspective::getRay()</code>&nbsp;and&nbsp;<code>CameraOrthographic::getRay()</code>. These methods take a camera-space&nbsp;<em>u,v</em>&nbsp;point as a parameter and return a 3D&nbsp;<code>ray3</code>. The code goes in&nbsp;<code>camera.cpp</code>.

</li>
<li>
<p dir="auto"><code>Scene::rayColor()</code>. This method returns the color along a 3D ray as a floating point&nbsp;<code>vec3</code>&nbsp;with components in the range [0,1]. The code goes in&nbsp;<code>scene.cpp</code>. The code for this is very short. You call simply call&nbsp;<code>Scene::closestIntersection()</code>, and, if there is one, return its&nbsp;<code>.material.color_diffuse</code>. Otherwise, you return black. (You will write a more sophisticated algorithm in the next assignment.)

</li>
</ul>
<p dir="auto">To implement&nbsp;<code>Scene::rayColor()</code>, you need to implement&nbsp;<em>its</em>&nbsp;helper method&nbsp;<code>Scene::closestIntersection()</code>, which returns the closest intersection with a shape in the scene along the given ray. The code for that goes in&nbsp;<code>scene.cpp</code>.

<p dir="auto">Finally, to implement&nbsp;<code>Scene::closestIntersection()</code>, you will need to implement&nbsp;<em>its</em>&nbsp;helper methods, which are&nbsp;<code>Shape::rayIntersect()</code>&nbsp;for each of the&nbsp;<code>Shape</code>&nbsp;subclasses. The code for those goes in&nbsp;<code>shape.cpp</code>. The&nbsp;<code>rayIntersect()</code>&nbsp;algorithms are what we have been deriving in class. You can find our derivations in&nbsp;<code>docs/Ray Shape Intersection Formula.txt</code>. You can find the pseudocode we created in class for the cylinder in&nbsp;<code>docs/raycasting_cylinder.py</code>. When you implement&nbsp;<code>rayIntersect()</code>, you must return information about the intersection in an&nbsp;<code>Intersection</code>&nbsp;struct. Set&nbsp;<code>.valid = true</code>&nbsp;if an intersection occurs and&nbsp;<code>.valid = false</code>&nbsp;otherwise. Remember that the incoming ray’s point&nbsp;<code>.p</code>&nbsp;and direction&nbsp;<code>.d</code>&nbsp;are in world-space. Convert them into object-space by multiplying them by&nbsp;<code>Shape</code>‘s method&nbsp;<code>transformInverse()</code>. It should be matrix times vector, not vector times matrix. Transformation matrices are 4×4, since they make use of homogeneous coordinates to perform translation. The homogeneous coordinate of a point should be 1, since points have fixed positions that should be translated. The homogeneous coordinate of a vector should be 0, since vectors do not have fixed positions in space and so translation is a no-op. (Imagine a vector&nbsp;<code>&lt;1,0,0&gt;</code>&nbsp;pointing along the x-axis. Translating it by&nbsp;<code>&lt;-2,0,0&gt;</code>&nbsp;should do nothing; adding the translation would result in the vector&nbsp;<code>&lt;-1,0,0&gt;</code>, which is the opposite of correct.)

<p dir="auto">For this raycasting assignment, you only must fill in the&nbsp;<code>.valid</code>,&nbsp;<code>.t</code>, and&nbsp;<code>.material</code>&nbsp;fields of the returned&nbsp;<code>Intersection</code>. To fill out the&nbsp;<code>.material</code>&nbsp;field, simply assign it from the&nbsp;<code>Shape</code>‘s&nbsp;<code>material()</code>&nbsp;method. Note that for the next assignment, you will have to fill out the rest of the fields. There’s no harm getting a head-start now. The&nbsp;<code>.position</code>&nbsp;and&nbsp;<code>.normal</code>&nbsp;fields should be stored in world-space. The incoming ray is in world-space, so use your t with the world-space ray’s position and direction to get a world-space position. Transform the object-space normal by&nbsp;<code>transpose(transformInverse())</code>&nbsp;to get a world-space normal.

<h2 dir="auto">C++ you need to know for this assignment</h2>
<p dir="auto">One of the most useful container types in C++ is&nbsp;<code>std::vector&lt;T&gt;</code>. It is a list/array class. The&nbsp;<code>&lt;T&gt;</code>&nbsp;means that it stores values with type&nbsp;<code>T</code>. (Because of the&nbsp;<code>&lt;&gt;</code>, it is called a templated type. Some programming languages call this generics.) If you have an&nbsp;<code>std::vector&lt;Foo&gt; v</code>, you can check if it is empty with&nbsp;<code>v.empty()</code>, you can get the number of elements it contains with&nbsp;<code>v.size()</code>, you can access an element i with&nbsp;<code>v[i]</code>&nbsp;or the bounds-checking version&nbsp;<code>v.at(i)</code>. There is also convenient syntactic sugar in C++ for iterating over all elements of a container. If you have a&nbsp;<code>std::vector&lt;ShapePtr&gt; my_shapes</code>, you can write:

<div class="snippet-clipboard-content notranslate position-relative overflow-auto">
<pre class="notranslate"><code>    for( const ShapePtr shape: my_shapes ) {
        ... shape-&gt;rayIntersect( ... ) ...
    }
</code></pre>
</div>
<p dir="auto">You may notice a&nbsp;<code>typedef</code>&nbsp;in one of the headers involving&nbsp;<code>std::shared_ptr&lt;T&gt;</code>. Treat a&nbsp;<code>std::shared_ptr&lt;T&gt;</code>&nbsp;as just a regular old&nbsp;<code>T*</code>&nbsp;(pointer). It is a reference counted pointer, so we don’t have to worry about freeing memory or memory leaks.

<h2 dir="auto"><a id="user-content-glm-and-cc-standard-library-functions-you-need-for-this-assignment" class="anchor" href="https://github.com/yig/graphics101-raycasting#glm-and-cc-standard-library-functions-you-need-for-this-assignment" aria-hidden="true"></a><code>glm</code>&nbsp;and C/C++ standard library functions you need for this assignment</h2>
<p dir="auto"><strong>glm.</strong>&nbsp;This assignment makes heavy use of the&nbsp;<code>glm</code>&nbsp;library for vector math. This library implements the&nbsp;<a href="https://www.khronos.org/opengl/wiki/Data_Type_(GLSL)" rel="nofollow">vector and matrix data types from the OpenGL Shading Language (GLSL)</a>, so substitute the keyword GLSL for glm when searching for documentation. You will make heavy use of&nbsp;<code>vec4</code>,&nbsp;<code>vec3</code>,&nbsp;<code>vec2</code>,&nbsp;<code>mat4</code>, possibly&nbsp;<code>mat3</code>, and functions like&nbsp;<code>dot(v1,v2)</code>,&nbsp;<code>inverse(m)</code>,&nbsp;<code>transpose(m)</code>, and&nbsp;<code>clamp(v, min_value, max_value)</code>. You can access the components of a&nbsp;<code>glm</code>&nbsp;vector&nbsp;<code>v</code>&nbsp;like an array with&nbsp;<code>v[i]</code>. Note that the vector and matrix types have the arithmetic operators +, -, *, / defined. The behavior depends on what is on the left and right of the operator. For example, if both sides are vectors,&nbsp;<code>v1+v2</code>&nbsp;or&nbsp;<code>v1/v2</code>&nbsp;will perform the addition or division on each corresponding element of the vectors. If one side is a scalar and the other is a vector or matrix,&nbsp;<code>v/5.0</code>&nbsp;will divide each element by 5.0. Finally, with a matrix and a vector,&nbsp;<code>m*v</code>&nbsp;will perform matrix multiplication. Note that if you have a&nbsp;<code>mat4 m</code>&nbsp;and then call&nbsp;<code>mat3(m)</code>, it will take the top-left 3×3 part of&nbsp;<code>m</code>. Similarly with the vec types; calling&nbsp;<code>vec3(v)</code>&nbsp;on a&nbsp;<code>vec4 v</code>&nbsp;will keep the first three xyz components. You can also create higher-dimensional matrices and vectors from lower-dimensional ones. For example, to create a&nbsp;<code>vec4</code>&nbsp;from a&nbsp;<code>vec3 v</code>, use&nbsp;<code>vec4(v,1.0)</code>. That sets the 4th component w to 1.0.

<p dir="auto"><strong>sqrt(x), fabs(x), lround(x), std::min(a,b), std::max(a,b)</strong>. They are part of C’s math.h (in C++ included as&nbsp;<code>&lt;cmath&gt;</code>) and C++’s&nbsp;<code>&lt;algorithm&gt;</code>. Note that&nbsp;<code>std::min</code>&nbsp;and&nbsp;<code>std::max</code>&nbsp;require both parameters to have the exact same type. If not, you will get a very long compiler error since they are generic functions written using C++ templates.

<p dir="auto">Note: This is not necessarily a complete list. I may be forgetting some!

<h2 dir="auto">Support code functions you need for this assignment</h2>
<p dir="auto"><strong>Image.</strong>&nbsp;The method&nbsp;<code>image.pixel(x,y) = c</code>&nbsp;to set the pixel x,y of an&nbsp;<code>Image</code>&nbsp;image to a&nbsp;<code>ColorRGBA8</code>&nbsp;color c. To get the width and height of the image, use&nbsp;<code>image.width()</code>&nbsp;and&nbsp;<code>image.height()</code>. The top left pixel is (0,0), not the bottom left pixel.

<p dir="auto"><strong>ColorRGBA8.</strong>&nbsp;To create an RGB&nbsp;<code>ColorRGBA8</code>&nbsp;color, use&nbsp;<code>ColorRGBA8( red, green, blue )</code>. Each of the parameters should be an integer number in the range [0,255], inclusive.
