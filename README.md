# cat_mathjax
A trimmed down version of the MathJax library for general use

the message of config is dist/config/TeX-AMS-MML_HTMLorMML.js

including the config of as follow:
MathJax.Hub.Config(
    {
        jax: ["input/TeX","output/HTML-CSS"],
        delayJaxRegistration: true,
        showProcessingMessages: false,
        messageStyle: "none",
        showMathMenu: false,
        showMathMenuMSIE: false,
        "HTML-CSS": {
            linebreaks: { automatic: true, width: "container" } ,
            availableFonts: ["TeX"]
  }
});

the demo is test.html
