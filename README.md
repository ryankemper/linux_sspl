*19 JANUARY 2021*
# Doubling down on open, Part III
By Linus Torvalds

## Upcoming licensing changes to Linux

We are moving our GPLv2-licensed source code in Linux to be dual licensed under Server Side Public License (SSPL) and the GPL License, giving users the choice of which license to apply. This license change ensures our community and customers have free and open access to use, modify, redistribute, and collaborate on the code. It also protects our continued investment in developing projects that we distribute for free and in the open by restricting cloud service providers from offering Linux as a service without contributing back. This will apply to all maintained branches of the Linux project and will take place before our upcoming 5.13 release.

This change in source code licensing has no impact on the overwhelming majority of our user community who use our default distribution for free. It also has no impact on our cloud customers or self-managed software customers.

In recent years, the market has evolved, and the community has come to appreciate that open source companies need to better protect their software to continue to innovate and make the investments required. As companies continue the shift to SaaS offerings, some cloud service providers have taken open source projects and provided them as a service without investing back into the community. Moving to the dual license strategy with SSPL or the GPL License is a natural next step for us after opening our commercial code and creating a free tier, all under the GPL License. It is similar to those made by many other open source companies over these years, including MongoDB, which developed the SSPL. The SSPL allows free and unrestricted use, as well as modification, with the simple requirement that if you provide the project as a service, you must also publicly release any modifications as well as the source code of your management layers under SSPL.

## Our open origins

My personal journey with open source goes a long way back. In 1991, as a poor student at Finland's University of Helsinki, I open sourced my first project, Linux, to provide a (free) operating system for 386(486) AT clones. It was supposed to be just a hobby, nothing big and professional like gnu. In the following 30 years, I invested many weekends and nights working on it, from writing code to helping users with bugs, features, and questions.

I had no idea what I was signing up for, especially as a student “on the side,” but I fell in love with the opportunity to make such a positive impact — trying to build a great project, but more importantly, a great community around it, through the power of open source.

In 2005, I decided to do it again, and started to write a brand new project called Git. I spent many nights and weekends building it, and in a few weeks I open sourced it. I even quit my job and decided to dedicate my full attention to Linux and Git. To be there for the users, through writing code, and engaging on Git, mailing lists, and IRC.

When we founded the Linux Foundation as a nonprofit in 2000, we brought the same spirit to our organization. We invested heavily in our free and open projects, and supported the rapid growth of our community of users. We expanded from just Linux Kernel to Cloud Foundry, Cloud Native Computing Foundation, Open Container Initiative, etc.

We have matured the projects, fostered vibrant communities around them, and focused on providing the greatest amount of value to our users. Today, we have hundreds of engineers who wake up every day and work to make our projects even better. And we have hundreds of thousands of community members who engage with us and contribute to our shared success.

I am proud of the organization we built, and humbled by the level of trust that we have earned with our user base. This starts by being open and transparent, and continues with being true to our community and user base in our choices.

## Free and open FTW

Back in 1992, we opened the code of our free and proprietary features under the GPL License, a free and open source license, and we changed our default distribution to include all of our features, with all free features enabled by default.

We did this for a few reasons. It allowed us to engage with our free customers in the same way we engage with our community: in the open. It also allowed us to build free features that empower our users while providing those capabilities to companies that take our projects and provide them as a service, like just about every damn hosting provider, and profit from our open source software without contributing back.

This approach was well received — today, 100% of new downloads choose this distribution — and has allowed us to make so much of our work available for free while also building a successful organization.

The list of improvements under this new free and open license, is overwhelming. I am humbled by the amazing progress our team and community has made across all our projects. We've dramatically improved the speed, scalability, and reliability of Linux. Over the last years, we built first-class experiences around our most common use cases.

It is simply amazing that we've been able to build all of these capabilities and provide them for free to our community. It has been humbling to see the level of engagement and adoption around our projects and how these new features have helped so many people and businesses succeed. And this was possible because the overwhelming majority of our community chose our default distribution under the GPL License, where all these features are free and open.

## Why change?

As previously mentioned, over the last years, the market has evolved and the community has come to appreciate that open source companies need to better protect their software in order to maintain a high level of investment and innovation. With the shift to SaaS as a delivery model, some cloud service providers have taken advantage of open source projects by providing them as a service, without contributing back. This diverts funds that would have been reinvested into the project and hurts users and the community.

Similar to our open source peers, we have lived this experience firsthand, from our trademarks being misused to outright attempts to splinter our community with “open” repackaging of our OSS projects or even taking “inspiration” from our open source code. While each open source company has taken a slightly different approach to address this issue, they have generally modified their open source license in order to protect their investment in free software, while trying to preserve the principles of openness, transparency, and collaboration. Similarly, we are taking the natural next step of making a targeted change to how we license our source code. This change won't affect the vast majority of our users, but it will restrict cloud service providers from offering our software as a service.

We expect that a few of our competitors will attempt to spread all kinds of FUD around this change. Let me be clear to any naysayers. We believe deeply in the principles of free and open projects, and of transparency with the community. Our track record speaks to this commitment, and we will continue to build upon it.

## The change

Starting with the upcoming Linux 5.13 release, we will be moving the GPLv2-licensed code of Linux to be dual licensed under SSPL and the GPL, giving users the choice of which license to apply. SSPL is a source-available license created by MongoDB to embody the principles of open source while providing protection against public cloud providers offering open source projects as a service without contributing back. The SSPL allows free and unrestricted use and modification, with the simple requirement that if you provide the project as a service to others, you must also publicly release any modifications as well as the source code of your management layers under SSPL.

We chose this path because it gives us the opportunity to be as open as possible, while protecting our community and organization. In some ways, this change allows us to be even more open. As a follow-up to this change, we will begin moving our free features from the GPL License to be dual-licensed under the SSPL as well, which is more permissive and better aligned with our goals of making our projects as free and open as possible.

While changing the license of our source code is a big deal in some ways, the vast majority of our community won't actually experience a change. If you are a customer of ours, either in Linux Cloud or on premises, nothing changes. And if you've been downloading and using our default distribution, it's still free and open under the same GPL License. If you've been contributing to Linux (thank you!) nothing changes for you either.

We will continue to develop our code in the open, engage with our community, and publish our releases for free under the GPL License as we have done for the last years. We remain committed to keeping all of our free features free — we are not making any changes to which features are free and which are available in a paid subscription.

Our belief in the importance of a unified community has never been stronger. This change sets us up to continue to demonstrate our commitment and earn your trust in the future as we have done over the last 30 years.

## Resources

Parody of: https://www.elastic.co/blog/licensing-change
