sa-tool-plantuml
================

[![Build Status](https://travis-ci.org/softasap/sa-tool-plantuml.svg?branch=master)](https://travis-ci.org/softasap/sa-tool-plantuml)

Easily create UML Diagrams from simple textual description. There are also numerous kind of available diagrams. It's also possible to export images in PNG, LaTeX, EPS, SVG.

Example of usage:

Simple

```YAML

     - {
         role: "sa-tool-plantuml"
       }


```

Advanced

```YAML

roles:

     - {
         role: "sa-tool-plantuml"
       }


```



Usage with ansible galaxy workflow
----------------------------------

If you installed the `sa-tool-plantuml` role using the command


`
   ansible-galaxy install softasap.sa-tool-plantuml
`

the role will be available in the folder `library/softasap.sa-tool-plantuml`
Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-tool-plantuml"
       }

```




Copyright and license
---------------------

Code is dual licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) and the [MIT License] (http://opensource.org/licenses/MIT). Choose the one that suits you best.

Reach us:

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

Discover other roles at  http://www.softasap.com/roles/registry_generated.html

visit our blog at http://www.softasap.com/blog/archive.html 
