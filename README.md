<!---<p align="center">
<img align="center" src="https://user-images.githubusercontent.com/46479689/211733894-16daa637-25f9-432a-b7e1-0689c39aef5a.svg" height="350px" ></p>--->
<p align="center">
<img align="center" src="https://github.com/S4F4Y4T/S4F4Y4T/assets/46479689/aadfa982-cff2-4391-b711-8bd22b798a90" height="350px" ></p>
<!---<p align="center">
<img align="center" src="https://github.com/S4F4Y4T/S4F4Y4T/assets/46479689/c6768854-da64-4589-bf5c-e6471998e286" height="350px" >
</p>--->
<h1 align="center">
Safayat Mahmud
</h1>
<p align="center">
<a href="https://safay.at/">
<picture height="24">
<source height="24" media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/S4F4Y4T/S4F4Y4T/master/icons/globe-white.svg">
<source height="24" media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/S4F4Y4T/S4F4Y4T/master/icons/globe.svg">
<img height="24" alt="Website" src="https://raw.githubusercontent.com/S4F4Y4T/S4F4Y4T/master/icons/globe.svg" width="100%">
</picture>
</a>&nbsp;&nbsp;
<a href="https://github.com/S4F4Y4T">
<picture height="24">
<source height="24" media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/S4F4Y4T/S4F4Y4T/master/icons/github-white.svg">
<source height="24" media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/S4F4Y4T/S4F4Y4T/master/icons/github.svg">
<img height="24" alt="Github" src="https://raw.githubusercontent.com/S4F4Y4T/S4F4Y4T/master/icons/github.svg" width="100%">
</picture>
</a>&nbsp;&nbsp; 
<a href="https://www.linkedin.com/in/S4F4Y4T/">
<picture height="24">
<source height="24" media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/S4F4Y4T/S4F4Y4T/master/icons/linkedin-white.svg">
<source height="24" media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/S4F4Y4T/S4F4Y4T/master/icons/linkedin.svg">
<img height="24" alt="Linkedin" src="https://raw.githubusercontent.com/S4F4Y4T/S4F4Y4T/master/icons/linkedin.svg" width="100%">
</picture>
</a>&nbsp;&nbsp;
<a href="https://twitter.com/S4F4Y4T">
<picture height="24">
<source height="24" media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/S4F4Y4T/S4F4Y4T/master/icons/twitter-white.svg">
<source height="24" media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/S4F4Y4T/S4F4Y4T/master/icons/twitter.svg">
<img height="24" alt="Twitter" src="https://raw.githubusercontent.com/S4F4Y4T/S4F4Y4T/master/icons/twitter.svg" width="100%">
</picture>
</a>&nbsp;&nbsp;

<a href="mailto:safayat.me@gmail.com">
<picture height="24">
<source height="24" media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/S4F4Y4T/S4F4Y4T/master/icons/mail-white.svg">
<source height="24" media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/S4F4Y4T/S4F4Y4T/master/icons/mail.svg">
<img height="24" alt="Mail" src="https://raw.githubusercontent.com/S4F4Y4T/S4F4Y4T/master/icons/mail.svg" width="100%">
</picture>
</a>&nbsp;&nbsp;
</p>


<br><br>

```php

class Portfolio extends Life
{
  public function __constructor()
  {
    parent::__construct();
  }


  public function index()
  {
    return array_merge(
        $this->about(),
        ['Skill' => $this->skill()]
    )
    
  }

  private function about()
  {
    return [
      'name' => 'Safayat Mahmud',
      'title' => 'Software Developer',
      'about' => 'I am Safayat Mahmud. A Web application developer passionate about creating highly scalable solutions that solve real life problems. I specialize in assisting businesses in resolving their challenges through technology.'
    ];
  }

  private function skill()
  {
    return [
        'Language' => ['PHP', 'JAVASCRIPT'],
        'Framework' => ['Laravel, 'Codeigniter', 'Expressjs', 'Tailwindcss', 'Vuejs'],
        'Others' => ['Mysql', 'Mongodb', 'Redis', 'Rest Api', 'JWT', 'Apache', 'CI/CD', 'Server Management', 'Web Security', 'Socket']
    ];
  }
  
}


```

<p align="center"><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=s4f4y4t&show_icons=true&locale=en&layout=compact&theme=dark" alt="s4f4y4t" />
</p>


