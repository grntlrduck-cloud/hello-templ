# Go templ - Hello TEMPL

This is just a super basic Go + templ hello world template.
In the past I struggled to set up templ syntax higlighting and formatting using nvim.
However, I am happy I finally made it work.
I experimented with very differen setups and I find the most satisfying, easy to use and yet minimal is [NvChad](https://nvchad.com).
Setting up templ syntax highliting with NvChad and Mason is easy and works like a charm, just follow the [guide](https://templ.guide/commands-and-tools/ide-support/#other-lsps-within-templ-files) in the templ docs.

## Why </> TEMPL?
Go is a simple, yet not (super) easy leanguage, with a great focus on developer productivity enabling
to write safe, concurrent and performat applications.
As I want to re-shape my protfolio from JVM (Java/Kotlin), TypeScript and Python to mainly Go and soon adding Rust.
I stumbled over TEMPL as good solution for SSR web app. 
Considering my personal perference and growing aversion towards endless framework hypes and poor performance as in the JVM and Node world,
TEMPL is a good alternative for React+Next.
The tooling appears to great for local development and adding htmx and tailwind is easy, allowing to move fast, if required.
In short, writing backend, infrastructure (AWS CDK or Terraform CDK) and frontend (TEMPL) all in one languages helps me to foucs
on more important things than managing different techs.
Moreover, Go+TEMPL empowers fast and efficient implementation, build and deploy of a SSR application using Public Cloud Solutions such as AWS CDN + Lambda@Edge.

Summary:
* Greate tooling and community
* Lightwight
* Integrates well with tailwind and htmx, or even React
* Go ecosystem
* Excelent web vitals due to SSR => important metric for SEO as we learned by the google leaks
* IDE Support out of the box for nvim, VSCode, and Intellij

## Outlook
I plan to implement a SSR web app to host a personal blog using Go, TEMPL, tailwind and htmx hosted on AWS with Lambda@Edge.

