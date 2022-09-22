### Starter File
<hr/>

1) In the components folder, a Layout component is made of the Head component,for SEO optimization, Header and Footer component. 
2) For 404 error, a NotFoundPage component.
3) Airbnb and Next eslint style libraries.
4) Stylesheet that include button and config styles.
5) Add a jsconfig.json file in the main project directory. Over here, add custom pathnames for easier import of files.
```
{
    "compilerOptions": {
        "baseUrl": ".",
        "paths":{
            "@/components/*" : ["components/*"],
            "@/styles/scss/*" : ["styles/scss/*"],
            "@/config/*" : ["config/*"],
            "@/context/*" : ["context/*"],
            "@/utilities/*" : ["utilities/*"] 
        }
    }
}
```




