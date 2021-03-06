## [v2.13.3](https://github.com/moovweb/xdn/releases/tag/v2.13.3) (2020-09-24)
## What’s Changed* XDN-5528 - Support hardcoded paths in Next.js rewrites (#510) @markbrocato---
## [v2.13.2](https://github.com/moovweb/xdn/releases/tag/v2.13.2) (2020-09-23)
## What’s Changed* Improve CLI output: Add a clearer deployment complete message. (#505) @markbrocato---
## [v2.13.1](https://github.com/moovweb/xdn/releases/tag/v2.13.1) (2020-09-23)
## What’s Changed* Don't add default router and service worker to the user's app on ever… (#507) @markbrocato---
## [v2.13.0](https://github.com/moovweb/xdn/releases/tag/v2.13.0) (2020-09-22)
## What’s Changed* [XDN-5422] Ensure that manual edits to the changelog are preserved (#506) @tristanlee85* XDN-5414 - Use --standalone to bundle dependencies when running nuxt … (#501) @markbrocato---
## [v2.12.1](https://github.com/moovweb/xdn/releases/tag/v2.12.1) (2020-09-22)
## What’s Changed* Update Sapper integration test to match the docs and not include node… (#504) @markbrocato* Remove obsolete domain check to enable wildcard reverse proxy in edge (#503) @ierceg* Allow relative paths when deep fetching from JSON (#498) @kevhender---
## [v2.12.0](https://github.com/moovweb/xdn/releases/tag/v2.12.0) (2020-09-21)
## What’s Changed* Apollo prefetching now uses GETs for all queries. (#500) @markbrocato---
## [v2.11.2](https://github.com/moovweb/xdn/releases/tag/v2.11.2) (2020-09-21)
## What’s Changed* Fix XDN-5364 - Next.js redirect to remove trailing slash prevents fal… (#496) @markbrocato* feat(CLI): Require node version: 12 or newer (#495) @adrien-k* [XDN-5258] Generate changelog when publishing release (#497) @tristanlee85* docs(README): add link to docs (#499) @adrien-k---
## [v2.11.1](https://github.com/moovweb/xdn/releases/tag/v2.11.1) (2020-09-16)
## What’s Changed* Update integration tests for POST/GET&xdn_prefetch=1 caching (#494) @phdunham* Next.js: Fix xdn build on windows (#492) @markbrocato* Fix coverage of nextRoutes (#493) @leotoll---
## [v2.11.0](https://github.com/moovweb/xdn/releases/tag/v2.11.0) (2020-09-16)
## What’s Changed* feat(frameworks): add Gatsby support + serve static root document (#474) @adrien-k---
## [v2.10.3](https://github.com/moovweb/xdn/releases/tag/v2.10.3) (2020-09-15)
## What’s Changed* Sapper: Remove extra service-worker route from the default routes.js file add… (#491) @markbrocato---
## [v2.10.2](https://github.com/moovweb/xdn/releases/tag/v2.10.2) (2020-09-15)
## What’s Changed* Next.js: pages/404.js now properly functions as the default fallback (#478) @leotoll* Fix bug in @xdn/sapper where the service worker would not be loaded i… (#490) @markbrocato---
## [v2.10.1](https://github.com/moovweb/xdn/releases/tag/v2.10.1) (2020-09-14)
## What’s Changed* Fix issue where pages/api/index.js was not being resolved by the XDN … (#488) @markbrocato---
## [v2.10.0](https://github.com/moovweb/xdn/releases/tag/v2.10.0) (2020-09-14)
## What’s Changed* feat(Errors): enhance user-facing fastly errors (#480) @adrien-k* Fix bug when using proxy with path option and a catch-all or optional… (#482) @markbrocato* Run request/response header manipulation in compute/trasnform (#483) @ierceg* Add functionality for prefetching GQL requests. (CU-a6axpw) (#451) @markbrocato* Add x-xdn-user-t to server-timing response header (#484) @ierceg* Bump node-fetch from 2.6.0 to 2.6.1 in /integration-tests/edge (#487) @dependabot* Bump node-fetch from 2.6.0 to 2.6.1 in /packages/core (#486) @dependabot* Add support for running Sapper apps with xdn run --production (#481) @markbrocato* Log 503 errors generated by shield (not just edge) (#479) @phdunham---
## [v2.9.0](https://github.com/moovweb/xdn/releases/tag/v2.9.0) (2020-09-09)
## What’s Changed* Fix XDN-on-XDN caching issues (#431) @ierceg* fix(MatchQuery) added edge config tests (#477) @KaarelKelk---
## [v2.8.0](https://github.com/moovweb/xdn/releases/tag/v2.8.0) (2020-09-08)
## What’s Changed* Adds support for the Sapper framework (#462) @markbrocato* feat(CLI): log failed build output in LD (#452) @adrien-k* Bump yargs-parser from 15.0.0 to 15.0.1 in /packages/cli (#475) @dependabot---
## [v2.7.0](https://github.com/moovweb/xdn/releases/tag/v2.7.0) (2020-09-07)
## What’s Changed* feat(MatchQuery) added criteria.query to match query params - XDN-533 (#461) @KaarelKelk* Optimize router loop unrolling by using equivalency chains (#472) @ierceg* fix(handler/logs): wrap console AND streams + remove globals (#471) @adrien-k* fix(Route) Matching headers returned true for single header match (#469) @KaarelKelk---
## [v2.6.4](https://github.com/moovweb/xdn/releases/tag/v2.6.4) (2020-09-04)
## What’s Changed* Lower the ACL limit to 900 to avoid Fastly's spurious API errors (#473) @ierceg---
## [v2.6.3](https://github.com/moovweb/xdn/releases/tag/v2.6.3) (2020-09-03)
## What’s Changed* Move static method to RouteGroup (#465) @markbrocato---
## [v2.6.2](https://github.com/moovweb/xdn/releases/tag/v2.6.2) (2020-09-02)
## What’s Changed* Fix bug where xdn init fails if a supported web framework is not dete… (#470) @markbrocato* Ignore query params when watching links to prefetch (#444) @kevhender---
## [v2.6.1](https://github.com/moovweb/xdn/releases/tag/v2.6.1) (2020-09-02)
## What’s Changed* Optimize x-xdn-original-qs to be injected only when qs are changed (#468) @ierceg---
## [v2.6.0](https://github.com/moovweb/xdn/releases/tag/v2.6.0) (2020-09-01)
## What’s Changed* Fix caching of static pages in NextRoutes. (#464) @markbrocato* Fix memory overconsumption in moov_hash (#463) @ierceg* Router static implementation for next (#428) @leotoll* Improve ci time (#447) @leotoll* Inject example x-xdn-geo- headers when running locally for easier testing. (#460) @phdunham* Emulate edge by injecting headers based on user-agent (#457) @phdunham---
## [v2.5.0](https://github.com/moovweb/xdn/releases/tag/v2.5.0) (2020-08-28)
## What’s Changed* feat(core/Router): prevent adding routes after fallback statement (#453) @adrien-k* fix(consoleWrapper): shim stdout/stderr to encapsulate in json (#432) @adrien-k* XDN-1438 - Fix bug where using an async callback in compute() results… (#456) @markbrocato* fix(@xdn/angular) Fix link command (#436) @KaarelKelk* Update the color scheme of the logo in the CLI. (#455) @markbrocato* Emulate edge's x-xdn-client-ip header when running locally (#454) @phdunham---
## [v2.4.2](https://github.com/moovweb/xdn/releases/tag/v2.4.2) (2020-08-26)
## What’s Changed* Corrected API documentation comment (#450) @ianand* Order predefined routes before dynamic routes (#440) @dijs* Angular fixups (#446) @tonylepmets---
## [v2.4.1](https://github.com/moovweb/xdn/releases/tag/v2.4.1) (2020-08-26)
## What’s Changed* PC-2330 - add Fastly API retry on 500 or 503 errors (#441) @phdunham* Disable request coalesing on shield (#448) @ierceg---
## [v1.48.1](https://github.com/moovweb/xdn/releases/tag/v1.48.1) (2020-08-26)
## What’s Changed* [v1 back port] Disable request coalescing on shield (#449) @ierceg---
## [v2.4.0](https://github.com/moovweb/xdn/releases/tag/v2.4.0) (2020-08-26)
## What’s Changed* Fix bug where context.params was undefined in getServerSideProps and getInitialProps in development when using xdn run.  (#443) @dijs* Adds a `compute()` function to `ResponseWriter` to compute responses in t… (#442) @markbrocato* Support service workers and prefetching in Nuxt apps when running in … (#445) @markbrocato---
## [v1.48.0](https://github.com/moovweb/xdn/releases/tag/v1.48.0) (2020-08-24)
## What’s Changed* v1: Add ability to completely turn off edge/browser caching for a route (back port of #435 to v1) (#437) @ierceg* Don't use latest tag any more (#434) @ierceg---
## [v2.3.1](https://github.com/moovweb/xdn/releases/tag/v2.3.1) (2020-08-23)
## What’s Changed* No changes - releasing as the previous release went out incorrectly as 2.2.1---
## [v2.3.0](https://github.com/moovweb/xdn/releases/tag/v2.3.0) (2020-08-22)
## What’s Changed* Add ability to completely turn off edge/browser caching for a route (#435) @ierceg---
## [v1.47.0](https://github.com/moovweb/xdn/releases/tag/v1.47.0) (2020-08-21)
## What’s Changed* [1.x] Adds a new timing API to allow users to track the performance of thei… (#430) (#433) @ierceg---
## [v2.2.0](https://github.com/moovweb/xdn/releases/tag/v2.2.0) (2020-08-20)
## What’s Changed* Adds a new timing API to allow users to track the performance of thei… (#430) @markbrocato* Upgrade next tests to 9.5 (#429) @ierceg* Fix issue during xdn build with Next.js apps that use source maps. (#423) @markbrocato* Add service worker to new Nuxt.js apps. (#427) @markbrocato* Fix bug when Next.js rewrites and redirects functions are async. (#425) @markbrocato---
## [v2.1.0](https://github.com/moovweb/xdn/releases/tag/v2.1.0) (2020-08-18)
## What’s Changed* Install @xdn/vue as a runtime dependency. (#421) @markbrocato* Make cors config optional for prefetch options (#424) @kevhender* Fix VCL code generation with conditions containing double quotes (#426) @ierceg* Add spartacus tests (#415) @leotoll* Make cors config optional for prefetch options (#420) @kevhender* Update "current" folder with latest when pushing new docs (#422) @kevhender---
## [v2.0.4](https://github.com/moovweb/xdn/releases/tag/v2.0.4) (2020-08-17)
## What’s Changed* Add NODE_ENV production to build lambdas (#419) @ierceg* Add appShell method to ResponseWriter. (#413) @markbrocato* PC-2313 - Fix nuxt es6 prod (#418) @markbrocato---
## [v2.0.3](https://github.com/moovweb/xdn/releases/tag/v2.0.3) (2020-08-15)
## What’s Changed* Support src/pages in Next.js apps. (#417) @markbrocato