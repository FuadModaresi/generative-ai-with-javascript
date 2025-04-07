ترجمه اسکریپت‌های زیر به فارسی به جز کد نمونه:

<div align="center"> 

<img src="./docs/images/logo.png" alt="" align="center" height="128" />

# هوش مصنوعی مولد برای مبتدیان با جاوااسکریپت

[![مجوز](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](https://github.com/microsoft/generative-ai-with-javascript/blob/main/LICENSE)
[![تماشای سری ویدیویی](https://img.shields.io/badge/Videos-d95652.svg?style=flat-square&logo=youtube)](https://aka.ms/genai-js)
[![PRs مورد پذیرش](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![دیسکورد Azure AI](https://dcbadge.limes.pink/api/server/kzRShWzttr)](https://discord.gg/kzRShWzttr)

⭐ اگر این مخزن را دوست دارید، آن را در GitHub ستاره دهید - خیلی کمک می‌کند!

[شروع کنید](#getting-started) • [درس‌ها](#lessons) • [ادامه یادگیری](#keep-learning)

</div>

آماده‌اید هوش مصنوعی مولد را در برنامه‌های جاوااسکریپتی خود ادغام کنید؟

این دوره شما را به یک *ماجراجویی سفر در زمان* می‌برد - با چهره‌های افسانه‌ای تاریخ با حال و هوایی متفاوت ملاقات کنید، در حالی که فناوری‌های هوش مصنوعی مولد را یاد می‌گیرید ✨

> [!IMPORTANT]  
> فضای متن‌باز! از این محتوا آزادانه استفاده کنید، تغییر دهید و به اشتراک بگذارید.

![نگاهی اجمالی به برنامه شخصیت‌ها](./docs/images/background.png)

## درخواست کمک - به ما در ترجمه کمک کنید!

به ما در ترجمه این دوره کمک کنید. هر درس در پوشه `lessons/` یک دایرکتوری `translations/` دارد. فایل ترجمه خود را به این صورت اضافه کنید `README.<کد زبان>.md`، مثلاً *README.fa.md*. - متشکرم.

## با جادوی هوش مصنوعی به تاریخ قدم بگذارید!

به یک تجربه یادگیری غوطه‌ورکننده با قدرت هوش مصنوعی مولد بپیوندید:  
- **درباره فناوری‌های هوش مصنوعی مولد یاد بگیرید**. اگر می‌خواستید هوش مصنوعی مولد و پتانسیل آن برای برنامه‌های خود را درک کنید، جای درستی هستید!

- **داستان‌های حماسی سفر در زمان**.
در هر درس با یک داستان جذاب، با چهره‌هایی مانند لئوناردو داوینچی، آدا لاولیس یا مونتزوما چت کنید.

- **برنامه همراه**. با استفاده از فناوری‌های هوش مصنوعی مولد با شخصیت‌های تاریخی تعامل داشته باشید ([مشاهده اخطار مسئولیت هوش مصنوعی ما](#responsible-ai-disclaimer)).

  ![تعامل با تاریخ از طریق گفتگو](./docs/images/character-chat.png) 

  پوشه [_app_](./app/) را برای [اجرای برنامه به صورت محلی](./docs/setup/README.md#option-2--running-the-app-locally) بررسی کنید یا از [GitHub Codespaces](./docs/setup/README.md) برای اجرای آنلاین استفاده کنید.

- **دسترسی پذیری اولویت دارد**. بخوانید، بشنوید - تگ‌های صوتی آن را زنده می‌کنند.

> "مثل یک کتاب کمیک با کد است!" — کاربر خوشحال

## شروع کنید

در طول این دوره نمونه‌های کد و تمرین‌های زیادی پیدا خواهید کرد، بنابراین شما را تشویق می‌کنیم که کد را در نسخه خود از این مخزن اجرا و آزمایش کنید:

1. دکمه **Fork** را در گوشه سمت راست بالای مخزن انتخاب کنید یا این دکمه را بزنید:
   [![Fork](https://img.shields.io/badge/Fork-Repository-blue?style=flat-square)](https://github.com/microsoft/generative-ai-with-javascript/fork)

2. در مخزن Fork شده خود، دکمه **Code** را بزنید، به تب **Codespaces** بروید و سپس **Create codespace** را انتخاب کنید.

   این یک محیط آنلاین از پیش پیکربندی شده برای شما ایجاد می‌کند. سپس می‌توانید از [GitHub Models](https://github.com/marketplace/models) برای اجرای نمونه‌های کد و تعامل با مدل‌های هوش مصنوعی به رایگان، بدون نیاز به تنظیمات اضافی استفاده کنید.

> [!NOTE]
>
> در حالی که GitHub Codespaces نقطه شروع سریع و آسانی فراهم می‌کند، می‌توانید نمونه‌های کد را [به صورت محلی](/docs/setup/README.md#option-2--running-the-app-locally) نیز اجرا کنید.
>
> بیشتر درباره [مفاهیم GitHub Codespaces و GitHub Models اینجا بیاموزید](/docs/setup/README.md).  

### توضیح درس

📦 هر درس شامل:

- یک **درس نوشته شده** با تکلیف و آزمون.
- یک **ویدیوی کوتاه** برای کمک به یادگیری بیشتر.
- **راه‌حل‌ها** برای هر تکلیف و آزمون.
- **شخصیت‌هایی** که می‌توانید با استفاده از [برنامه همراه](./app) ما با آنها تعامل داشته باشید، که هوش مصنوعی مولد را نشان می‌دهد.

## درس‌ها

🗃️ فهرست مطالب

| # | لینک درس  | توضیحات |
| ---- | ----------- | ----------- |
| 1 | [مقدمه‌ای بر هوش مصنوعی مولد و مدل‌های زبانی بزرگ برای توسعه‌دهندگان جاوااسکریپت](./lessons/01-intro-to-genai) | مبانی هوش مصنوعی مولد و مدل‌های زبانی بزرگ، کاربردها و محدودیت‌های آنها در جاوااسکریپت، و نحوه استفاده از هوش مصنوعی برای بهبود تجربه کاربری را درک کنید. |
| 2 | [اولین برنامه هوش مصنوعی خود را بسازید](./lessons/02-first-ai-app) | محیط توسعه خود را تنظیم کنید، یک برنامه پایه بنویسید و promptهای سیستم را درک کنید. |
| 3 | [مهندسی prompt](./lessons/03-prompt-engineering) | مبانی مهندسی prompt، تکنیک‌ها و meta-promptها برای نتایج بهتر هوش مصنوعی را یاد بگیرید. |
| 4 | [خروجی ساختاریافته](./lessons/04-structured-output) | خروجی ساختاریافته، نحوه استخراج داده از promptها و ارائه آن در قالب‌های مختلف مانند JSON برای مصرف آسان‌تر را یاد بگیرید. |
| 5 | [تولید تقویت شده با بازیابی (RAG)](./lessons/05-rag) | مبانی RAG، نحوه ادغام داده‌های خارجی و استفاده از آن برای پاسخ‌های هوش مصنوعی مرتبط‌تر و دقیق‌تر را یاد بگیرید. |
| 6 | فصل‌های اضافی به زودی اضافه می‌شوند! | ... |

درس‌های جدید به مرور به دوره اضافه خواهند شد، پس منتظر بمانید!

## ادامه یادگیری

🙌 پس از اتمام این دوره، می‌توانید با بررسی منابع اضافی ما به یادگیری ادامه دهید.

<details>
<summary>🎬سری ویدیویی</summary>

| # | جلسه | توضیحات | اسلایدها | دمو | اسکریپت | ویدیو |
|---|---------|-------------|--------|------|--------|-------|
| 0 | معرفی سری | این سری و محتوای آن را معرفی می‌کند. | [pptx](/videos/slides/00-intro.pptx) / [pdf](/videos/slides/pdf/00-intro.pdf) | - | [اسکریپت](/videos/sessions/00-intro.md) | [📺](https://www.youtube.com/watch?v=vLYtDgs_zx8&list=PLlrxD0HtieHi5ZpsHULPLxm839IrhmeDk&index=1) |
| 1 | آنچه باید درباره مدل‌های زبانی بزرگ بدانید | بررسی می‌کند که مدل‌های زبانی بزرگ چیستند، چگونه آموزش می‌بینند، چگونه کار می‌کنند و محدودیت‌های آنها چیست. | [pptx](/videos/slides/01-llms.pptx) / [pdf](/videos/slides/pdf/01-llms.pdf) | [دمو](/videos/demos/01-llms/) | [اسکریپت](/videos/sessions/01-llms.md) | [📺](https://www.youtube.com/watch?v=GQ_2OjNZ9aA&list=PLlrxD0HtieHi5ZpsHULPLxm839IrhmeDk&index=2)  |
| 2 | تکنیک‌های ضروری مهندسی prompt | تکنیک‌های عملی مهندسی prompt برای بهره‌برداری بهتر از مدل‌های هوش مصنوعی. | [pptx](/videos/slides/02-prompt-engineering.pptx) / [pdf](/videos/slides/pdf/02-prompt-engineering.pdf) | [دمو](/videos/demos/02-prompt-engineering/) | [اسکریپت](/videos/sessions/02-prompt-engineering.md) | [📺](https://www.youtube.com/watch?v=gQ6TlyxBmWs&list=PLlrxD0HtieHi5ZpsHULPLxm839IrhmeDk&index=3)  |
| 3 | بهبود دقت و قابلیت اطمینان هوش مصنوعی با RAG | تولید تقویت شده با بازیابی را معرفی می‌کند تا از هوش مصنوعی با داده‌های خود استفاده کنید. | [pptx](/videos/slides/03-rag.pptx) / [pdf](/videos/slides/pdf/03-rag.pdf) | [دمو](/videos/demos/03-rag/) | [اسکریپت](/videos/sessions/03-rag.md) | [📺](https://www.youtube.com/watch?v=xkFOmx5yxIA&list=PLlrxD0HtieHi5ZpsHULPLxm839IrhmeDk&index=4) |
| 4 | توسعه هوش مصنوعی خود را با LangChain.js تسریع کنید | مفاهیم اصلی چارچوب LangChain.js و نحوه استفاده از آن برای تسریع توسعه هوش مصنوعی را پوشش می‌دهد. | [pptx](/videos/slides/04-langchainjs.pptx) / [pdf](/videos/slides/pdf/04-langchainjs.pdf) | [دمو](/videos/demos/04-langchainjs/) | [اسکریپت](/videos/sessions/04-langchainjs.md) | [📺](https://www.youtube.com/watch?v=02IDU8eCX8o&list=PLlrxD0HtieHi5ZpsHULPLxm839IrhmeDk&index=5) |
| 5 | اجرای مدل‌های هوش مصنوعی روی ماشین محلی با Ollama | نحوه ادغام مدل‌های هوش مصنوعی محلی در گردش کار توسعه شما را نشان می‌دهد. | [pptx](/videos/slides/05-local-models.pptx) / [pdf](/videos/slides/pdf/05-local-models.pdf) | [دمو](/videos/demos/05-local-models/) | [اسکریپت](/videos/sessions/05-local-models.md) | [📺](https://www.youtube.com/watch?v=dLfNnoPv4AQ&list=PLlrxD0HtieHi5ZpsHULPLxm839IrhmeDk&index=6) |
| 6 | شروع به کار با هوش مصنوعی به صورت رایگان با Phi-3 | آزمایش با Ollama و مدل Phi-3 مستقیماً از مرورگر شما. | [pptx](/videos/slides/06-playground.pptx) / [pdf](/videos/slides/pdf/06-playground.pdf) | [دمو](/videos/demos/06-playground/) | [اسکریپت](/videos/sessions/06-playground.md) | [📺](https://www.youtube.com/watch?v=Ds32MS9SHzU&list=PLlrxD0HtieHi5ZpsHULPLxm839IrhmeDk&index=7) |
| 7 | مقدمه‌ای بر Azure AI Foundry | سفر خود را با Azure AI Foundry آغاز کنید. | [pptx](/videos/slides/07-ai-foundry.pptx) / [pdf](/videos/slides/pdf/07-ai-foundry.pdf) | [دمو](/videos/demos/07-ai-foundry/) | [اسکریپت](/videos/sessions/07-ai-foundry.md) | [📺](https://www.youtube.com/watch?v=9Mo-VOGk8ng&list=PLlrxD0HtieHi5ZpsHULPLxm839IrhmeDk&index=8) |
| 8 | ساخت برنامه‌های هوش مصنوعی مولد با Azure Cosmos DB | برنامه‌های هوش مصنوعی مولد با Azure Cosmos DB و جستجوی برداری بسازید. | [pptx](/videos/slides/08-cosmos-db.pptx) / [pdf](/videos/slides/pdf/08-cosmos-db.pdf) | [دمو](/videos/demos/08-cosmos-db/) | [اسکریپت](/videos/sessions/08-cosmos-db.md) | [📺](https://www.youtube.com/watch?v=-GQyaLbeqxQ&list=PLlrxD0HtieHi5ZpsHULPLxm839IrhmeDk&index=9)  |
| 9 | ابزارها و سرویس‌های Azure برای میزبانی و ذخیره برنامه‌های هوش مصنوعی | برنامه‌های هوش مصنوعی را با استفاده از ابزارهای Azure بسازید، مستقر کنید و مقیاس دهید. | [pptx](/videos/slides/09-azure-tools.pptx) / [pdf](/videos/slides/pdf/09-azure-tools.pdf) | - | [اسکریپت](/videos/sessions/09-azure-tools.md) | [📺](https://www.youtube.com/watch?v=WB6Fpzhwyug&list=PLlrxD0HtieHi5ZpsHULPLxm839IrhmeDk&index=10) |
| 10 | استریم خروجی هوش مصنوعی مولد با پروتکل چت هوش مصنوعی | استریم را به راحتی با پروتکل چت هوش مصنوعی در برنامه‌های خود ادغام کنید. | [pptx](/videos/slides/10-chat-protocol.pptx) / [pdf](/videos/slides/pdf/10-chat-protocol.pdf) | [دمو](/videos/demos/10-chat-protocol/) | [اسکریپت](/videos/sessions/10-chat-protocol.md) | [📺](https://www.youtube.com/watch?v=fzDCW-6hMtU&list=PLlrxD0HtieHi5ZpsHULPLxm839IrhmeDk&index=11) |

برای مشاهده صفحه کامل منابع، به این [صفحه مرور ویدیوها](/videos/README.md) مراجعه کنید.

</details>

<details>
<summary>🎒 دوره‌های دیگر</summary>

- [هوش مصنوعی مولد برای مبتدیان](https://aka.ms/genai-beginners)
- [هوش مصنوعی مولد برای مبتدیان دات‌نت](https://github.com/microsoft/Generative-AI-for-beginners-dotnet)
- [هوش مصنوعی مولد با جاوااسکریپت](https://github.com/microsoft/generative-ai-with-javascript)
- [هوش مصنوعی برای مبتدیان](https://aka.ms/ai-beginners)
- [عامل‌های هوش مصنوعی برای مبتدیان - یک دوره](https://github.com/microsoft/ai-agents-for-beginners)
- [علم داده برای مبتدیان](https://aka.ms/datascience-beginners)
- [یادگیری ماشین برای مبتدیان](https://aka.ms/ml-beginners)
- [امنیت سایبری برای مبتدیان](https://github.com/microsoft/Security-101) 
- [توسعه وب برای مبتدیان](https://aka.ms/webdev-beginners)
- [اینترنت اشیا برای مبتدیان](https://aka.ms/iot-beginners)
- [توسعه XR برای مبتدیان](https://github.com/microsoft/xr-development-for-beginners)
- [مسلط شدن بر GitHub Copilot برای برنامه‌نویسی جفتی](https://github.com/microsoft/Mastering-GitHub-Copilot-for-Paired-Programming)
- [مسلط شدن بر GitHub Copilot برای توسعه‌دهندگان سی‌شارپ/دات‌نت](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers)
- [ماجراجویی Copilot خود را انتخاب کنید](https://github.com/microsoft/CopilotAdventures)
</details>

همچنین منابع اضافی به صورت [آموزش‌ها، نمونه کد و بیشتر](/docs/additional-resources.md) پیدا خواهید کرد.

## اخطار مسئولیت هوش مصنوعی

> [!IMPORTANT]
> اخطار: این مخزن حاوی محتوای تخیلی تولید شده توسط هوش مصنوعی است. شخصیت‌های تاریخی به تصویر کشیده شده در اینجا پاسخ‌هایی را با استفاده از هوش مصنوعی مولد تولید می‌کنند، که مبتنی بر داده‌های آموزشی است. هر پاسخ تولید شده توسط این شخصیت‌ها نمایانگر دیدگاه‌ها یا نقل قول‌های واقعی آنها نیست. این محتوا صرفاً برای مقاصد سرگرمی در نظر گرفته شده است. [اصول مسئولیت هوش مصنوعی مایکروسافت اینجا](https://www.microsoft.com/en-us/ai/principles-and-approach/)

## تعامل با جامعه

[![دیسکورد Azure AI](https://dcbadge.limes.pink/api/server/kzRShWzttr)](https://discord.gg/kzRShWzttr)
