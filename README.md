# CA TWO
---
## Company Background
Brew Beer Company {Dublin): You can order beer tailored to your own liking online and you can go in store and purchase their own original beer flavours. Some employees are working in UK and the store and website has been running since 2007. 

## IT Setup:
Two on-premise servers that carry out a combination of functions. One server is a database server used for storing data and also acts as a web server responsible for running their online store. Second server is for e-mails and filing (Powercert Animated Videos, 2020, 00:48). They are located in a small space in their IT office. They exchange files and e-mails using Thunderbird and SMTP (Simple Mail Transfer Protocol) with their server (Powercert Animated Videos, 2020, 06:17). There is a computer at their store till for in store transactions. 

## Recommendations:
* I recommend incorporating the cloud in their IT infrastructure.  Instead of a server for emailing and filing they can use cloud-based services such as Microsoft Office 365. It is easier to sync multiple devices and they can log in from anywhere. This enables easy collaboration since files and e-mails aren’t hosted on just one desktop (Miller, 2008, p. 27).

* Instead of a web server and spending a lot of money upfront for the service to be able to provide up to 75% of their base load, they can use the cloud where you pay for what you use. The cloud adjusts to their computing needs so during off peak seasons they don’t waste money on the service that they don’t use and you can increase the service when there is high demand (Miller, 2008, p. 25).  

* Since the store has been running for 15 years, legacy systems is one drawback from moving the business to the cloud. Migrating legacy systems and data to the cloud is difficult due to high migration costs and unexpected failures such as data loss. They may choose to continue using their legacy systems because they still work and it is too much of a hassle (Fahmideh et al 2017 pp. 1-4). However, they can do a hybrid of on-premise and cloud services. They can keep data between their on-site database server and public cloud. The cloud server’s built in APIs (application programming interface) help free the applications from obsolete operating system and aids communication between on-premise and cloud applications (‘Akana’, no date). If they want more control over their data and infrastructure it would be better to use Infrastructure as a Service such as Microsoft Azure (Cloudian, no date). I recommend public over private cloud because it is a small enterprise so they may not have enough time (private requires more management since public cloud is managed by the providers) and money for private cloud (Vikas et al, 2013, p. 82).

***
# Reference List
---
Akana (no date) ‘Cloud APIs’. Available at: https://www.akana.com/resources/cloud-apis (Accessed: 7 December 2022)

Cloudian (no date). Available at: https://cloudian.com/guides/hybrid-it/hybrid-cloud-architecture/ (Accessed: 1 December 2022)

Fahmideh M., Daneshgar F., Beydoun G. and Rabhi F. (2017) ‘Challenges in migrating legacy software systems to the cloud—an empirical study’, *Information Systems* [online]. 67, pp.1-4. Available at: https://www.researchgate.net/publication/315836686_Challenges_in_migrating_legacy_software_systems_to_the_cloud-an_empirical_study (Accessed: 7 December 2022)

Miller M. (2008). *Cloud Computing: Web-Based Applications That Change the Way You Work and Collaborate Online*. New York City, New York: Que Publishing. Available at: https://ptgmedia.pearsoncmg.com/images/9780789738035/samplepages/0789738031_Sample.pdf (Accessed: 7 December 2022)

Powercert Animated Videos (2020) *What is a Server? Servers vs Desktops Explained*. Available at https://youtu.be/UjCDWCeHCzY (Accessed: 1 December 2022)

Vikas S., Gurudatt K., Vishnu M. and Prashant K. (2013). ‘Private Vs Public Cloud’, *International Journal of Computer Science & Communication Networks* [online]. 3(2), pp. 82-82. Available at: https://www.researchgate.net/profile/Gurudatt Kulkarni/publication/258253155_Private_Vs_Public_Cloud/links/00b7d5279d2e6dfb22000000/Private-Vs-Public-Cloud.pdf (Accessed: 7 December 2022)

---


# Docker Getting Started Tutorial

This tutorial was written with the intent of helping folks get up and running
with containers and is designed to work with Docker Desktop. While not going too much 
into depth, it covers the following topics:

- Running your first container
- Building containers
- Learning what containers are
- Running and removing containers
- Using volumes to persist data
- Using bind mounts to support development
- Using container networking to support multi-container applications
- Using Docker Compose to simplify the definition and sharing of applications
- Using image layer caching to speed up builds and reduce push/pull size
- Using multi-stage builds to separate build-time and runtime dependencies

## Getting Started

If you wish to run the tutorial, you can use the following command after installing Docker Desktop:

```bash
docker run -d -p 80:80 docker/getting-started
```

Once it has started, you can open your browser to [http://localhost](http://localhost).

## Development

This project has a `docker-compose.yml` file, which will start the mkdocs application on your
local machine and help you see changes instantly.

```bash
docker compose up
```

## Contributing

If you find typos or other issues with the tutorial, feel free to create a PR and suggest fixes!

If you have ideas on how to make the tutorial better or want to suggest adding new content, please open an 
issue first before working on your idea. While we love input, we want to keep the tutorial scoped to new-comers.
As such, we may reject ideas for more advanced requests and don't want you to lose any work you might
have done. So, ask first and we'll gladly hear your thoughts!
