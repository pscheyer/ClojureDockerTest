#table of contents
1. [Current Progress](#current-progress)
2. [Background](background)

## Current Progress
20151107 1304CST


## Background
20151107 1241CST
Working off of http://blog.juxt.pro/posts/beanstalk.html to learn how to use clojure with docker. End goal is to go through Clojure for the Brave and True using Docker containers for easy deployment. The article suggests Beanstalk as a platform as a service to deploy Docker containers running clojure onto Amazon Web Services. 

Some basic terminology: Docker containers are tiny virtual computers which configure themselves according to a 'dockerfile' containing basically a set of scripts of what the virtual computer needs to achieve its purpose. The virtual computer is known as a 'container,' like a shipping container, because it's standardized in operations, a subset of the system, and portable. 

Platform as a Service refers to applications which offer automated internals of a platform, such as auto-scaling, load-balancing, and other arcane terms which i don't understand. PaaS does that for you. Infrastructure as a service gives you access to tools which can do these things but doesn't autoconfigure them.

Clojure is a programming language which is a fusion of Lisp and Java. Lisp is a functional language great for metaprogramming. Functional language means that the language does not modify its inputs over the course of its operations. Thanks to this, it does not tend to have the same sorts of error as imperative programming languages (such as C or Python or Ruby or their derivatives). However, they have their own problems- such languages tend to not have good support in the form of libraries of functions and algorithms for specific purposes. There are many reasons for this, one of the main ones being that experts in such languages tend to simply use their metaprogramming features to rewrite the language for new tasks or generate an appropriate library after studying what they are trying to accomplish. This is cool but involves a lot of reinvention of completed problems.

Enter Java, an imperative language based on virtual machines which has an extensive collection of libraries of functions for specific tasks. These libraries are also compartmentalized due to the basis on virtual machines.

Clojure attempts to combine the functional language features of Lisp with the libraries of Java. As such it has some strengths and some weaknesses of each- it is not quite as powerful as purer Lisps, and Java is not the fastest imperative language nor can it take advantage of the low-level strengths of a C language. Also Clojure cannot develop on mobile platforms easily. (though there are [lein-droid](https://github.com/clojure-android/lein-droid) and for iOS [lein-fruit](https://github.com/oakes/lein-fruit) which look promising.)

But, Clojure does offer fast and powerful functional programming with access to strong libraries, and is built for web development thanks to Java. So it's worth a look for people interested in rapid prototyping of web applications with potential for quick and effective changes. 

Clojure has been extended to also use Javascript, a web scripting language recently stretched to perform many web functions and one of the most actively developed language frameworks in existence due to the proliferation of web development and the ease of access which javascript allows- it is mostly an extension to basic html and CSS, and so you can start with a functional html website (like a blog), start adding javascript, and get into advanced ux development and some simple backend stuff through a gradual learning process, as opposed to many other languages which require extensive knowledge prior to effective implementation.


Anyway, those are the basic terms. Now on to the project. 20151107 1302CST

