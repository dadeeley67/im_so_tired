+++
title = "YNAB Clone in Rust"
date = 2024-02-01

[taxonomies]
categories = ["software", "rust"]

[extra]
repo_path = "dadeeley67/budget-tool"
+++

Learning Rust by copying my favorite budget app.

<!-- more -->

{{ img(path="@/projects/project-1/code.png", alt="Some Rust code from my budget_tool project", caption="main.rs", quality = 100, extended_width_pct=0.2) }}

&nbsp;

## I want to learn Rust. 

Shocker, I’m sure. Everyone seems to want to learn Rust, if the Internet is to be believed. The success of channels like [No Boilerplate](https://www.youtube.com/@NoBoilerplate), [Code to the Moon](https://www.youtube.com/@codetothemoon), [chris biscardi](https://www.youtube.com/@chrisbiscardi), and [Let’s Get Rusty](https://www.youtube.com/@letsgetrusty), to name a few, is a testament to that fact. Also, the fact that Rust has [made its way into the Linux Kernel](https://www.zdnet.com/article/rust-in-linux-where-we-are-and-where-were-going-next/) is another good sign that it is here to stay, and that it is worth learning about. 

I specifically want to learn more about backend development, and I want to use Rust as the language for that learning. I was *technically* a full-stack developer at my previous job, but in the day-to-day, I was mostly a front-end developer. Which was great, and I really enjoy front-end development. However, I feel a desire to expand my horizons, and I would like to live up to the idea of a full-stack developer more than I currently do.

## ~~Copying~~ (*cough cough*) Flattering YNAB

So, to that end, this project is my attempt to do these things by creating my own version of one of my favorite applications, [You Need A Budget](https://www.ynab.com/)! I enjoy using YNAB for my personal budgeting, and I believe anyone looking for a new tool/philosophy on how to manage their finances should check out YNAB. It took me literally five or six attempts at using this app to ***finally*** get the hang of it, but now that I have, I’m not sure how I could use anything else. 

That being said, I don’t love connecting my accounts to the app with Plaid and automating all of those transactions. It works fine, mostly, but I don’t feel super comfortable connecting all of these accounts to an app, and I also believe that to really get a hold of your finances, you need to be hands-on with them. *Every single transaction* should pass through your fingertips when you make it, and when you account for it. It is more tedious, but it is what forces you to come to terms with how you spend your money. 

You can, of course, not connect your accounts to YNAB and then use it manually as I’ve described, and I will probably end up doing that soon, now that I’ve settled into a good rhythm of using it every day and keeping tabs on my money. However, in the meantime, why not try and recreate it for myself? I can’t learn anything without actually using it in a tangible way, and of course:

> “Imitation is the sincerest form of flattery that mediocrity can pay to greatness.” - Oscar Wilde

So off I go, trying to flatter YNAB. Maybe they’ll notice me and give me a high-five or something. That’d be neat.