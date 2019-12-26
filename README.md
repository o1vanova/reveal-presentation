[My Presentation](https://presentation-vue.netlify.com)

<h2>Transcription</h2>

`(Slide - Presentation name)`<br>
Hello!
My name is Olga, and today I'd like to talk to you about Vue.js. My presentation is divided into four parts. First, I will speak about the origins of Vue.js. Then I will look at advantages over other frameworks and I will try to answer the question of why you should use it. Next, I will talk about the basics of using Vue.js. And finally, I will demonstrate how it works.

`(Slide - History)`<br>
Now, let's start with history. Vue was created by Evan You after working for Google. His job involved a lot of prototyping in the browser. And Evan wanted to create something that allows him to make it as fast as possible. At that time some of the projects used Angular but Angular was too heavy. So in 2013, Evan started to work something, which would be lightweight and consist only of minimal features. In February 2014 he put the first release of Vue.js on Github. Although it was the first Evan's project, it got several hundred stars in the first week.

`(Slide - Companies)`<br>
Nowadays, its popularity is still growing. This picture illustrates that even large companies use Vue.js. You can see such industry giants as Facebook, Netflix, Adobe, Alibaba, GitLab, Behance, Oracle and more. And I have to tell you, that is not the most complete list.

`(Slide - Reasons)`<br>
We shall now talk about the reasons for the popularity of Vue.js. One of the main reasons is

`(Slide - How does it work?)`<br>
Every Vue application starts by creating a new Vue instance with the Vue function. After I created a Vue instance, I can pass an options object to it. To provide the Vue instance an existing DOM element, I have to add an option 'el'. It can be a CSS selector string or an actual HTMLElement. Most often, an identifier is used as a CSS selector.

`(Slide - Directives)`<br>
An HTML page can contain some directives. Let's learn more about a number of them. The directive "v-if" is used to conditionally render a block. The block will only be rendered if the directive’s expression returns a truthy value. It is also possible to add an "else block" with the directive "v-else". Another option for conditionally displaying an element is the "v-show" directive. The difference is that an element with "v-show" will always be rendered and remain in the DOM. The directive "v-for" is used to render a list of items based on an array. The directive "v-on" is used to attach event listeners that invoke methods on the Vue instance. And the directive "v-bind" is used with "class" and "style". It helps to dynamically change the attributes of an element.

`(Slide - Demonstration)`<br>
Now, I want to demonstrate how to create a simple Vue application. I have already had a basic Html page with a simple structure and empty content in the body. Then, I add a link to include Vue. My page doesn't need to work in offline mode, so to establish a link between my page and Vue I will use only this string. Or, you can download Vue.js on your computer and import it in your project. I have added a unique identifier "myId" to the div tag. So my project is ready to use Vue.js. Now I create a new instance Vue in a file with the extension .js.

This presentation will cover only the most important functions. For more details, see [full documentation](https://vuejs.org/).

`(Slide - Thank you)`<br>
Thank you for your attention!
