<h1>Spring Boot / Spring Security Bootstrap Demo</h1>

<a href="https://bluemix.net/deploy?repository=https://github.com/papicella/SpringBootSecurityBootstrap" 
target="_blank"><img src="http://bluemix.net/deploy/button.png" alt="Bluemix button" /></a>

Login credentials are found in WebSecurityConfig.java file as follows

```
    @Autowired
    public void configureGlobal(AuthenticationManagerBuilder auth) throws Exception {
        auth
                .inMemoryAuthentication()
                .withUser("pas").password("welcome1").roles("USER");
    }
```

Screen Shots

Landing Page ->

![alt tag](https://dl.dropboxusercontent.com/u/15829935/bluemix-docs/images/bluemix-springsecurity1.png)

Form Athentication Login Page ->

![alt tag](https://dl.dropboxusercontent.com/u/15829935/bluemix-docs/images/bluemix-springsecurity2.png)

Welcome Page once Athenticated ->

![alt tag](https://dl.dropboxusercontent.com/u/15829935/bluemix-docs/images/bluemix-springsecurity3.png)
