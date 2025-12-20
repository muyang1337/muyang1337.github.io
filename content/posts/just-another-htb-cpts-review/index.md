+++
title = 'Just Another HTB CPTS Review'
author = 'muyang1337'
date = '2025-12-19T15:43:29+11:00'
description = 'This was my first security certification, and tackling it without prior hands-on exam experience made it especially challenging. While there are already many CPTS reviews available, I hope this post can act as a supplementary resource for the current CPTS exam, focusing on the mistakes I made and the lessons I learned along the way.'
tags = ["CPTS", "HTB", "Offensive Security", "Certification", "Penetration Testing"]
categories = ["Security", "Reflections"]
image = "cover.webp"
+++

## Time Line and Milestones

- started Learning on the HTB Academy - `Dec/2023`
- Landed an offensive security role with HTB enterprise support - `March/2025`
- Completed the `Penetration Tester Path` - `19/Oct/2025`
- Started the first CPTS exam attempt - `08/Nov/2025`
- Started the second CPTS exam attempt - `03/Dec/2025`
- Submited the second attempt - `10/Dec/2025`
- Passed and obtained the certification - `13/Dec/2025`

So yes - the entire journey took almost two years from start to finish. I don’t have statistics to prove this, but I believe my journey was significantly longer than most CPTS candidates. From reviews and conversations with others, most people seem to complete the path within one year. That's a fair estimation if you plan to start the CPTS journey. Why did it take me two year? In short, most of my time and energy went into landing my first security role. This included doing HTB weekly boxes throughout the season to improve my ranking, polishing my résumé, applying for roles across different companies, and preparing for interviews. All of this took far more time than I initially expected. On top of that, I had no prior knowledge with Windows or Active Directory, which made learning those concepts from scratch especailly challenging. That said, the outcome was worth it. I didn't give up and I eventually became a HTB certified penetration testing specialist. Looking back on these two years, there are many things I wish I had known earlier to avoid unnecessary frustration. Below are some lessons and tips I’d like to share with anyone who is starting — or about to start — their CPTS journey.

## Tips 

### Time Box Your Learning

I do have a reasonable explanations for taking this long, but deep down I know I could have been far more efficient and that would significantly reduce the duration to get certified. My learning strategy was to take as much time as I thought I needed - and that assumption turned out to be dangerous. A lot of time was lost due to zoning out and frequent context switching. This can be improved by setting clear goals and time-boxing each learning session. For example, set a goal like: "Complete Windows Privilege Escalation Section 2 in one hour". Focus on that goal. Finish it. Move on. I only started using this approach late in my learning process, but it made a significant difference.

### Take Comprehensive Notes As You go

This is something I did consistently, and it paid off. I wrote down everything I didn’t understand. It’s boring and time-consuming, but absolutely worth it. Imagine how satisfying it feels when a detailed note you wrote weeks earlier ends up solving a problem during the CPTS exam — that happened to me more than once. While HTB Academy provides a search function, it’s no substitute for notes written in your own words and structured around how you think.

### Respect The Exam Preparation

The CPTS journey has three distinct stages:

1. Complete `Penetration Tester Path`.
2. Prepare specifically for the CPTS exam.
3. Take the exam.

Do not make the same mistake I did: Don't overlook stage 2. After completing 100% of the Penetration Tester Path, I rushed straight into the exam, eager to earn the certification as soon as possible. I didn’t give the preparation phase the respect it deserved.

There are three main preparation resources:.
1. Do AEN(Attack Enterprise Network) blindly
2. [Official preparation list](https://app.hackthebox.com/tracks/76) provided by HTB
3. [Unofficial preparation list](https://www.youtube.com/playlist?list=PLidcsTyj9JXItWpbRtTg6aDEj10_F17x5) provided by Ippsec

In my case:
- I didn't do AEN blindly.
- I didn't check any box in unofficial preparation list.
- I did 50% of boxes in official preparation list. 

During the exam, I encountered four blockers that were actually covered by preparation materials I had skipped. (one in AEN, two in official preparation list, one in unofficial preparation list). Completing all preparation materials would have saved me at least three full days during the exam. To be clear, you shouldn’t expect the exam to mirror these boxes exactly. However, they are extremely helpful and often provide critical inspiration when you’re stuck.
### Know When You Go Too Far

The CPTS exam is designed to resemble real-world environments. One key difference between real-world scenarios and tailored lab boxes is noise.

Lab boxes usually have a clear intended path with limited distractions. Real-world environments, however, are noisy and filled with rabbit holes — and sometimes the correct path looks just like another rabbit hole.

For example, you might exploit vulnerability A, which leads to vulnerability B, which hints at vulnerability C. You invest significant time into C, only to get completely stuck. In a lab environment, this often means you missed something and need to dig deeper. In the CPTS exam, however, it’s often a sign that you’ve gone too far down the wrong path.

Knowing when to stop — and when to step back — is a critical skill. Based on my experience, these situations should raise red flags:

- You need to rely on very recent techniques (within ~6 months of the exam).
- You must modify system configurations to make the exploit work.
- You feel the need to reboot the target machine.
- You suspect the exam environment itself is broken.
- You are considering building a highly customized brute-force wordlist.

### AI Is Not Your Friend In The Exam

AI tools are everywhere today, but they are surprisingly unhelpful in the CPTS exam. In real-world-style environments, AI often encourages you to dig deeper into rabbit holes instead of helping you step back. More than once, AI tools pushed me in the wrong direction. In the worst case, ChatGPT gave me a completely incorrect answer to a specific problem, while Gemini provided vague guidance that was far from the correct path. This is likely why HTB doesn’t restrict AI usage during the exam. All the knowledge you need is already covered in the Academy and preparation materials. In my experience, no AI is needed during the exam — and I would personally recommend avoiding it altogether.

### Tips Are Time-Sensitive
There’s no doubt that you’ll find a large number of reviews and tips online. However, all advice — including what’s shared in this blog — is only valid for a limited time, as HTB continuously updates and improves its exam challenges. A good example is the expectation around difficulty. Many existing resources describe Flag 1 and Flag 9 as the “bosses” of the exam. In the current version, however, Flag 8 turned out to be the most challenging. This may change again in the future.For that reason, it’s better to treat tips, advice, or even “hints” from Reddit as general guidance rather than silver bullets.

## The End

Overall, the CPTS experience was highly rewarding. One noticeable improvement is how much easier it has become for me to understand modern security research reports, especially those related to Windows and Active Directory. That said, not all modules are equal. Some modules feel less polished than others, and certain explanations can be confusing or unintuitive. Still, earning the CPTS certification places you at a solid junior-to-mid-level penetration testing foundation. CPTS focuses heavily on traditional enterprise environments and does not cover modern areas like cloud security in depth. It’s a strong milestone — but far from the end of the journey. Hacking is a lifelong pursuit. So keep learning, stay curious, and keep hacking the planet.
