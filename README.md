<a href="#" target="_blank"><img src="https://storage.googleapis.com/fns-blog/public/frontend/assets/images/page/about/banner.jpg" /></a>

# My Roadmap to Becoming a Full Stack Developer: My Skill Trees
```mermaid
  stateDiagram-v2
    ProgrammingLanguages: Programming Languages
    Backend --> ProgrammingLanguages
      note left of ProgrammingLanguages : I'm knowledgeable with backend programming languages.
      state Programming ProgrammingLanguages {
        C/C++
        CSharp:C#
        PHP
      }
    VersionControlSystems: Version Control Systems
    ProgrammingLanguages --> VersionControlSystems
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
        MSSQL: MS SQL
        MySQL: MySQL
      }
      state APIs {
        REST: REST
        JSONAPIs: JSON APIs
      }
    WebServers: Web Servers
    Backend --> WebServers
      state WebServers {
        Apache
      }
    ProgrammingLanguages --> Frameworks
      state Frameworks {
        Laravel:Laravel (PHP Framework)
        CodeIgniter:CodeIgniter (PHP Framework)
      }
    Laravel --> JSONAPIs : I'm knowledgeable with build APIs using Laravel
    Laravel --> MySQL : I'm knowledgeable with build laravel eloquent.
```
> - [C Developers Guide](../../../C-Developer-s-Guide)
>   - [Beginners](../../../C-Developer-s-Guide/tree/beginners)

> - [JavaScript Developers Guide](../../../JavaScript-Developer-s-Guide)
>   - [Beginners](../../../JavaScript-Developer-s-Guide/tree/anvanced)

```mermaid
  stateDiagram-v2
    Frontend --> PWAs
      state PWAs {
        Storage
        Notifications
      }
    Frontend --> Frameworks
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
> - [TypeScript Developers Guide](../../../TypeScript-Developer-s-Guide)
>   - [Beginners](../../../TypeScript-Developer-s-Guide/tree/beginners)

> - [React Examples](../../../react-examples)
>   - [Components: Popup](../../../react-examples/tree/components/popup)

```mermaid
  stateDiagram-v2
    SmartContracts: Smart Contracts
    Blockchain --> SmartContracts
    ProgrammingLanguages: Programming Languages
    SmartContracts --> ProgrammingLanguages
    state ProgrammingLanguages {
        Solidity
    }
    SmartContracts --> Testing
    state Testing {
        UnitTests: Unit Tests
        IntegrationTests: Integration Tests
        CodeCoverage: Code Coverage
    }
```
> - [Solidity Developers Guide](../../../Solidity-Developer-s-Guide)
>   - [Beginners](../../../Solidity-Developer-s-Guide/tree/beginners)

```mermaid
  stateDiagram-v2
    OperatingSystem: Operating system
    DevOps --> OperatingSystem
    Windows: Windows
    OperatingSystem --> Windows
    Linux: Linux
    OperatingSystem --> Linux
    state Linux {
        Ubuntu: Ubuntu
        Oracle: Oracle
        KaliLinux: Kali
        Debian: Debian
    }
    CloudServices: Cloud Services
    Linux --> CloudServices
    Windows --> CloudServices
    state CloudServices {
        GoogleCloud: Google Cloud Computing Services
        OracleCloud: Oracle Cloud Infrastructure
        AWS: Amazon Web Services
    }
    CloudDesignPatterns: Cloud Design Patterns
    CloudServices --> CloudDesignPatterns
    state CloudDesignPatterns {
        DataManagement: DataManagement
        Managementandmonitoring: Management and monitoring
    }
```

## My Roadmap to Becoming a Full Stack Developer: My Projects

> - [Laravel 9 & React & TypeScript with CRM Project](../../../fnsoftworks-web-app)
> - [React & TypeScript with Ethereum dApp Project](../../../nft-minting-collection-app)
> 
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
