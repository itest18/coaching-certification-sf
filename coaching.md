Coaching SF
===========================

#### **1) Bundles**
* Namming conventions  
* Code organization  
* Controllers  
* Views  
* Resources    

[- The Bundle System](https://symfony.com/doc/2.3/book/bundles.html)  
[- Best Practices for Reusable Bundles](https://symfony.com/doc/2.3/cookbook/bundles/best_practices.html)  
[- How to Override any Part of a Bundle](https://symfony.com/doc/2.3/cookbook/bundles/override.html)  
[- How to Load Service Configuration inside a Bundle](https://symfony.com/doc/2.3/cookbook/bundles/extension.html)  
[- How to Create Friendly Configuration for a Bundle](https://symfony.com/doc/2.3/cookbook/bundles/configuration.html)  

---

#### **2) Controllers**
* The Request object  
* The Response object  
* The Session object  
* The Cookie object  
* The internal redirects  
* The HTTP redirects  
* The 404 exceptions  

[- Controller](https://symfony.com/doc/2.3/book/controller.html)  
[- How to Customize Error Pages](https://symfony.com/doc/2.3/cookbook/controller/error_pages.html)  

---

#### **3) Routing**
* Configuration (YAML / XML / PHP & annotations)  
* Adding constraints to urls parameters  
* Applying default values to urls parameters  
* Generating urls based on routing configuration  

[- Routing](https://symfony.com/doc/2.3/book/routing.html)  
[- How to Force Routes to always Use HTTPS or HTTP](https://symfony.com/doc/2.3/cookbook/routing/scheme.html)  
[- How to Allow a "/" Character in a Route Parameter](https://symfony.com/doc/2.3/cookbook/routing/slash_in_parameter.html)  
[- How to Configure a Redirect without a custom Controller](https://symfony.com/doc/2.3/cookbook/routing/redirect_in_config.html)  
[- How to Use HTTP Methods beyond GET and POST in Routes](https://symfony.com/doc/2.3/cookbook/routing/method_parameters.html)  

---

#### **4) Templating with Twig**
* Automatic escaping  
* Template inheritance  
* Global variables  
* Functions & filters  
* Template inclusions  
* Loops & conditions  
* Urls generation  
* Action rendering  
* Translation helpers

[- Creating and Using Templates](https://symfony.com/doc/2.3/book/templating.html)  
[- How to Inject Variables into all Templates (i.e. global Variables)](https://symfony.com/doc/2.3/cookbook/templating/global_variables.html)  
[- How to Use PHP instead of Twig for Templates](https://symfony.com/doc/2.3/cookbook/templating/PHP.html)  
[- TwigBundle Configuration](https://symfony.com/doc/2.3/reference/configuration/twig.html)  
[- Twig Template Form Function and Variable Reference](https://symfony.com/doc/2.3/reference/forms/twig_reference.html)  
[- Symfony Twig Extensions](https://symfony.com/doc/2.3/reference/twig_reference.html)  

---

#### **5) Forms**
* Designing form types  
* Processing a form  
* Built-in form field types  
* Form rendering in Twig  
* Form security (CSRF protection)  
* Data transformers  
* Form events  

[- Forms](https://symfony.com/doc/2.3/book/forms.html)  
[- How to Customize Form Rendering](https://symfony.com/doc/2.3/cookbook/form/form_customization.html)  
[- How to Use Data Transformers](https://symfony.com/doc/2.3/cookbook/form/data_transformers.html)  
[- How to Dynamically Modify Forms Using Form Events](https://symfony.com/doc/2.3/cookbook/form/dynamic_form_modification.html)  
[- How to Create a Custom Form Field Type](https://symfony.com/doc/2.3/cookbook/form/create_custom_field_type.html)  
[- How to Create a Form Type Extension](https://symfony.com/doc/2.3/cookbook/form/create_form_type_extension.html)  
[- How to Unit Test your Forms](https://symfony.com/doc/2.3/cookbook/form/unit_testing.html)  

---

#### **6) Data Validation** 
* Validating a PHP object  
* Built-in validation constraints  
* Validation constraints scopes  
* Validation groups  

[- Validation](https://symfony.com/doc/2.3/book/validation.html)  

---

#### **7) Dependency Injection** 
* The service container  
* Global configuration parameters  
* Built-in Symfony services  
* Registering new custom services  
* Dependency injection tags  
* Semantic bundle configuration  
* Compiler passes  

[- Service Container](https://symfony.com/doc/2.3/book/service_container.html)  
[- How to Work with Compiler Passes in Bundles](https://symfony.com/doc/2.3/cookbook/service_container/compiler_passes.html)  
[- The Dependency Injection Tags](https://symfony.com/doc/2.3/reference/dic_tags.html)  

---

#### **8) Security**
* Authentication  
* Authorization  
* User providers  
* Firewalls  
* Users  
* Encoders  
* Roles  
* Access Control Rules  

[- Security](https://symfony.com/doc/2.3/book/security.html)  
[- How to Impersonate a User](https://symfony.com/doc/2.3/cookbook/security/impersonating_user.html)  
[- How to Use Voters to Check User Permissions](https://symfony.com/doc/2.3/cookbook/security/voters.html)  
[- How to Force HTTPS or HTTP for different URLs](https://symfony.com/doc/2.3/cookbook/security/force_https.html)  
[- How to Secure any Service or Method in your Application](https://symfony.com/doc/2.3/cookbook/security/securing_services.html)  

---

#### **9) HTTP Caching**
* Types of cache (browser, proxies & reverse proxies)  
* Expiration (Expires, Cache-Control)  
* Validation (Etag, Last-Modified)  
* Client side caching  
* Server side caching  
* Edge Side Includes 

[- HTTP Cache](https://symfony.com/doc/2.3/book/http_cache.html)  

---

#### **10) The Command Line Interface**
* Symfony built-in commands  
* Custom console commands  
* Command configuration  
* Options & arguments definition  
* Input & Output handling  
* Command helpers  

[- How to Create a Console Command](https://symfony.com/doc/2.3/cookbook/console/console_command.html)  
[- The Console Component](https://symfony.com/doc/2.3/components/console/introduction.html)  
[- How to Use the Console](https://symfony.com/doc/2.3/cookbook/console/usage.html)  
[- How to Call a Command from a Controller](https://symfony.com/doc/2.3/cookbook/console/command_in_controller.html)  
[- How to Enable Logging in Console Commands](https://symfony.com/doc/2.3/cookbook/console/logging.html)  
[- Using Events](https://symfony.com/doc/2.3/components/console/events.html)  

---

#### **11) Automated testing**
* Functional tests  
* The Client object  
* The Crawler object  
* The Profile object  
* Accessing internal framework objects  
* Configuring the client  
* Request / response inspection  

[- Testing](https://symfony.com/doc/2.3/book/testing.html)  


#### **12) SF Architecture**
* The Client / Server model  
* The HTTP request/response  
* Namming conventions  
* Coding standards  

[- Symfony and HTTP Fundamentals](https://symfony.com/doc/2.3/book/http_fundamentals.html)  
[- Hypertext Transfer Protocol](https://www.ietf.org/rfc/rfc2616.txt)  

[- Configuring Symfony (and Environments)](https://symfony.com/doc/2.3/book/configuration.html)  
[- How to Organize Configuration Files](https://symfony.com/doc/2.3/cookbook/configuration/configuration_organization.html)  
[- How to Master and Create new Environments](https://symfony.com/doc/2.3/cookbook/configuration/environments.html)  
[- How to Override Symfony's default Directory Structure](https://symfony.com/doc/2.3/cookbook/configuration/override_dir_structure.html)  
[- Using Parameters within a Dependency Injection Class](https://symfony.com/doc/2.3/cookbook/configuration/using_parameters_in_dic.html)  
[- How to Set external Parameters in the Service Container](https://symfony.com/doc/2.3/cookbook/configuration/external_parameters.html)  
[- Understanding how the Front Controller, Kernel and Environments Work together](https://symfony.com/doc/2.3/cookbook/configuration/front_controllers_and_kernel.html)  

[- Coding Standards](https://symfony.com/doc/2.3/contributing/code/standards.html)  

