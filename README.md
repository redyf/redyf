# 📜 About me
[![visitcount](https://visitcount.itsvg.in/api?id=redyf&label=Profile%20Views&color=1&icon=6&pretty=true)](https://visitcount.itsvg.in)
```elixir
defmodule User do
  def create_user do
    %{
      name: "Mateus Alves",
      role: "Software Developer",
      languages: ["Portuguese", "English"],
      education: "BSc @ UNIJORGE"
    }
    |> (fn user ->
          """
          Name: #{user.name}
          Role: #{user.role}
          Spoken Languages: #{Enum.join(user.languages, ", ")}
          Education: #{user.education}
          """
        end).()
    |> IO.puts()
  end
end

User.create_user()

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
  
<img height="180em" src="https://denvercoder1-github-readme-stats.vercel.app/api/?username=redyf&show_icons=true&include_all_commits=true&count_private=true&theme=react&hide_border=true&bg_color=0d1117&title_color=A594FD&icon_color=A594FD"/>
<img height="180em" src="https://denvercoder1-github-readme-stats.vercel.app/api/top-langs/?username=redyf&langs_count=8&layout=compact&theme=react&hide_border=true&bg_color=0d1117&title_color=A594FD&icon_color=A594FD"/>

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
