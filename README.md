# 📜 About me
[![visitcount](https://visitcount.itsvg.in/api?id=redyf&label=Profile%20Views&color=1&icon=6&pretty=true)](https://visitcount.itsvg.in)
```nix
{pkgs ? import <nixpkgs> {}}: let
  softwareEngineer = {
    name = "Mateus Alves";
    role = "Software Engineer";
    spokenLanguages = ["Portuguese" "English"];
    spokenLanguagesString = builtins.concatStringsSep ", " softwareEngineer.spokenLanguages;
  };
in
  with pkgs;
    writeTextFile {
      name = "mateus-alves-info.txt";
      text = ''
        Name: ${softwareEngineer.name}
        Role: ${softwareEngineer.role}
        Spoken Languages: ${softwareEngineer.spokenLanguagesString}

        Thanks for dropping by, hope you find some of my work interesting.
      '';
    }
```
## 🛠️ Skills 

<details open>
  <summary><b>📌 Programming languages</b></summary>
  <br>

[![Programming Languages](https://skillicons.dev/icons?i=c,js,typescript,python,go)](https://skillicons.dev)
</details>

<details open>
  <summary><b>📚 Libraries and Frameworks</b></summary>
  <br>

[![Libraries and Frameworks](https://skillicons.dev/icons?i=react,nextjs,express,jest,tailwind)](https://skillicons.dev)
</details>

<details open>
  <summary><b>🎨 Markup and Style Languages</b></summary>
  <br>

[![Markup and Style Languages](https://skillicons.dev/icons?i=html,css,markdown)](https://skillicons.dev)
</details>

<details open>
  <summary><b>🧠 DevOps</b></summary>
  <br>

[![DevOps Tools](https://skillicons.dev/icons?i=docker,nix,aws,vercel)](https://skillicons.dev)
</details>

<details open>
  <summary><b>🗄️ Databases</b></summary>
  <br>
    
[![Databases](https://skillicons.dev/icons?i=mysql,postgres)](https://skillicons.dev)
</details>

<details open>
  <summary><b>🔧 Software and Tools</b></summary>
  <br>
    
[![Software and Tools](https://skillicons.dev/icons?i=git,github,neovim,linux,obsidian,figma,raspberrypi)](https://skillicons.dev)
</details>

## 📊 Github stats and extras

<details>
  <summary><b>🧬 Public statuses</b></summary>
  <br>
  
<img height="180em" src="https://github-readme-stats.vercel.app/api?username=redyf&show_icons=true&bg_color=00000000"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=redyf&layout=compact&bg_color=00000000"/>

</details>
<br>

<details>
  <summary><b>🏆 Trophies</b></summary>
<br>

  <img src="https://github-profile-trophy.vercel.app/?username=redyf&theme=tokyonight&row=2&no-bg=true&column=3&margin-w=15&margin-h=15"/>
</details>

<br>

<details>
  <summary><b>🔥 Streak</b></summary>
  <br>

[![GitHub Streak](https://streak-stats.demolab.com?user=redyf&theme=transparent&date_format=%5BY%20%5DM%20j)](https://git.io/streak-stats)
</details>
