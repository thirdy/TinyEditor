# TinyEditor

## Usage

Paste the following code into your browser address bar:

    data:text/html,<body oninput="document.querySelector('iframe').srcdoc=h.value+'<style>'+c.value+'</style><script>'+j.value+'</script>'"><style>textarea,iframe{float:right;width:100%;height:50%}body{margin:0}textarea{width:33.33%;font-size:18}</style><textarea placeholder=JS id=j></textarea><textarea placeholder=CSS id=c></textarea><textarea placeholder=HTML id=h></textarea><iframe>
    
    

If you want to read the code, check out [index.html](https://github.com/umpox/TinyEditor/blob/master/index.html)
