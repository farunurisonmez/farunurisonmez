<a href="#" target="_blank"><img src="https://storage.googleapis.com/fns-blog/public/frontend/assets/images/page/about/banner.jpg" /></a>

# My Roadmap to Becoming a Full Stack Developer: My Skill Trees
```mermaid
  stateDiagram-v2
    Backend --> Languages:l
      note left of Languages : I'm knowledgeable with backend programming languages.
      state Languages {
        C/C++
        CSharp
        PHP
      }
    VersionControlSystems: Version Control Systems
    Languages --> VersionControlSystems
      state VersionControlSystems {
        GitHub
      }
    Testing: Testing
    VersionControlSystems --> Testing
      state Testing {
        CICD: CI / CD
      }
    RelationalDatabases: Relational Databases
    Backend --> RelationalDatabases
    RelationalDatabases --> APIs
      state RelationalDatabases {
        MySQL: MySQL
      }
      state APIs {
        JSONAPIs: JSON APIs
      }
    WebServers: Web Servers
    Backend --> WebServers
      state WebServers {
        Apache
      }
```
> - [C Developers Guide](../../../C-Developer-s-Guide)
>   - [Beginners](../../../C-Developer-s-Guide/tree/beginners)
```mermaid
  stateDiagram-v2
    Frontend --> PWAs
      state PWAs {
        Storage
        Notifications
      }
    Frontend --> Frameworks:l
      note left of Frameworks : I'm knowledgeable with frontend frameworks.
      state Frameworks {
        React
      }
    VersionControlSystems: Version Control Systems
    Frameworks --> VersionControlSystems
      state VersionControlSystems {
        GitHub
      }
    Frontend --> APIs
      state APIs {
        Graphql: GraphQL
      }
    Frameworks --> Libraries
      state Libraries {
        StyledComponents: Styled Components
        note left of StyledComponents : CSS Framework
        Bootstrap: Bootstrap
        note left of Bootstrap : CSS Library
      }
    TypeCheckers:Type Checkers
    Frameworks --> TypeCheckers
       state TypeCheckers {
        TypeScript: TypeScript
      }
```
> - [React Examples](../../../react-examples)
>   - [Popup Components](/guides/content/editing-an-existing-page)

<p align="center">I believe Open Source is for EVERYONE, yes YOU TOO! Join me on my <a href="https://www.youtube.com/channel/UC7edB0EhgVO7dAVY8-NiVTA?sub_confirmation=1">YouTube channel</a></p>

<p align="center"><b>Join our inclusive community <a href="http://community.farunurisonmez.com">FNS Community</a>!</b> Coming Soon</p>
<h5 align="center">Would you like to donate to our community?</h5>
<p align="center">Sign up to my community <a href="http://farunurisonmez.com/newsletters">FNS Newsletter</a> to be kept up-to-date monthly with upcoming events, community achievements and more</p>

<p align="center">
  <a href="http://youtube.com/channel/UC7edB0EhgVO7dAVY8-NiVTA?sub_confirmation=1">
    <img src="https://img.shields.io/youtube/channel/subscribers/UC7edB0EhgVO7dAVY8-NiVTA?style=for-the-badge&logo=youtube&label=Youtube&color=blue" />
  </a>
  </br>
  <a href="http://farunurisonmez.github.io">
    <img src="https://img.shields.io/website?style=for-the-badge&logo=github&logoColor=white&label=farunurisonmez.github.io&down_color=lightgrey&down_message=offline&up_color=black&up_message=Github Page&url=https%3A%2F%2Fshields.io" />
 </a>
   <a href="http://farunurisonmez.com">
    <img src="https://img.shields.io/website?style=for-the-badge&logo=earn&label=farunurisonmez.com&down_color=lightgrey&down_message=offline&up_color=black&up_message=Blog&url=http://farunurisonmez.com" />
 </a>
<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=farunurisonmez&show_icons=true&theme=tokyonight" />
  <img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=farunurisonmez&theme=tokyonight" />
  <img width="96%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=farunurisonmez&layout=compact&theme=tokyonight" />
</p>
