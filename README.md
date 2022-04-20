<p align="center">
  <a href="https://github.com/fwiedmann/icof">
    <img src="logo.png" height="200">
  </a>

<h3 align="center">Awesome hosting list</h3>

  <p align="center">
    This list is for everyone who wants to deploy a web application + backend on a budget.
  </p>
  <div align="center">
   <img src="https://img.shields.io/badge/made%20with-%E2%9D%A4%EF%B8%8F-lightgrey">
   </div>
</p>

## Contribution

Feel free to contribute if you know any alternatives compared to the hosting providers below.

How to:

1. Fork this repository
2. Make your changes
3. Lint the `README.md` with [Markdown all in one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
4. Create a PR on this repository

## List

| Provider                                                                         | Costs | vCPU           | Memory GB    | Storage                                                                                                   | Bandwidth                 | IP             | Snapshots                                             | Backup                                                        | Locations                                                                                                                          | Extras                                                                                 | Cons                                                                                       |
| -------------------------------------------------------------------------------- | ----- | -------------- | ------------ | --------------------------------------------------------------------------------------------------------- | ------------------------- | -------------- | ----------------------------------------------------- | ------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| [Hetzner Cloud CX11](https://www.hetzner.com/cloud)                              | 4.15€ | 1 (Intel)      | 2            | 20 GB                                                                                                     | 20 TB (1.19€ per add. TB) |                | Manual snapshot's: 0.0119€/GB = 0.238€/ 20GB Snapshot | up to automatically 7 Backups: 20% of instance price  = 0.83€ | Germany, Finland                                                                                                                   | Free firewall rules                                                                    |                                                                                            |
| [Hetzner Cloud CPX11](https://www.hetzner.com/cloud)                             | 4.75€ | 2 (AMD)        | 2            | 40 GB                                                                                                     | 20 TB (1.19€ per add. TB) |                | Manual snapshot's: 0.0119€/GB = 0.238€/ 40GB Snapshot | up to automatically 7 Backups: 20% of instance price  = 0.95€ | Germany, Finland, USA                                                                                                              | Free firewall rules                                                                    |                                                                                            |
| [Hetzner Cloud CX11](https://www.hetzner.com/cloud)                              | 5.83€ | 2 (Intel)      | 4            | 40 GB                                                                                                     | 20 TB (1.19€ per add. TB) |                | Manual snapshot's: 0.0119€/GB = 0.476€/ 40GB Snapshot | up to automatically 7 Backups: 20% of instance price  = 0.95€ | Germany, Finland                                                                                                                   | Free firewall rules                                                                    |                                                                                            |
| [NetCup VPS 200 G10s](https://www.netcup.de/vserver/vps.php#v-server-details)    | 2.99€ | 2 vCore        | 2GB DDR4 ECC | 40 GB                                                                                                     | 80 TB                     | Dedicated IPv4 | Snapshots (Copy-On-Write)                             | -                                                             | Nürnberg (Germany), Wien (Austria), connected to Anexia Backbone Europe                                                            | see [list of features](https://www.netcup.de/vserver/vps.php#v-server-details)         |                                                                                            |
| [user space](https://uberspace.de/)                                              | 5€    | "A fair slice" | 1.5          | 10TB free, Each 10GB/3€ up to 100GB                                                                       |                           | Shared IPv4    |                                                       | Free. Daily backups keep for 7 days, weekly for 7 weeks       |                                                                                                                                    | Free SSL, SetUp DBs, Webserver, Web Backends via CLI                                   | No real VM, no docker install, no package management                                       |  |
| [X Small civo](www.civo.com)                                                     | 5$    | 1              | 1            | 25GB                                                                                                      | 1TB                       | N/A            | N/A                                                   | N/A                                                           | N/A                                                                                                                                |                                                                                        |
| [Digital Ocean App platform](https://www.digitalocean.com/products/app-platform) | 5$    | Shared CPU     | 512 MiB      | [Direct mounts are not available](https://docs.digitalocean.com/products/app-platform/how-to/store-data/) | 40 GiB Outbound           | Dynamic IPv4   | N/A                                                   | N/A                                                           | [NYC	AMS	SFO	SGP	LON	FRA	TOR	BLR ](https://docs.digitalocean.com/products/platform/availability-matrix/#app-platform-availability) | 3 static sites, automatic HTTPS, bring your custom domain, global CND, DDoS mitigation | [Checkout the limits section](https://docs.digitalocean.com/products/app-platform/#limits) |