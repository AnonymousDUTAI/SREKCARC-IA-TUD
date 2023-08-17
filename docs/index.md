<figure markdown>
  ![Image title](./images/title.png){ width="600" }
</figure>

# Chapter 0.写在前面的话

## 0.1 Docs 声明


**声明**

本 Docs 是数十位作者根据兴趣自发撰写完成，版权属于本书编委会。在本书撰写过程中，我们始终以“中立”和“公益”为原则，没有接受其他任何组织任何形式的支持。未经编委会许可，任何组织或个人不得违反相应的版权条例抄袭、转载、摘编、修改本书内容；不得将本书用于商业目的；不得对本 Docs 原意进行曲解、修改和未授权的大范围分发。本 Docs 是一部集合了二十多篇独立文章的作品集锦。每一小节均由不同作者撰写。在编写本 Docs 时，作者们听取了大量同学的意见和观点，并尽可地将各种观点统一在手册的框架下。这样做的目的，是希望能向读者传达更多可供参考的观点和意见。

本 Docs 并不构成任何明确的行动建议，因此作者不承担由此产生的衍生责任。本 Docs 作者不能保证手册内容中没有对其他组织的误解和偏见。Docs 内容的正确性并没有经过权威审查，手册作者无法保证 Docs 中的方法始终有效。Docs 作者亦无力确认手册是否违反了读者所在地的各种法规，请各位读者参照当地行政规定。如有违反，请您停止阅读并立即销毁手册的任何副本。对于未经授权传播 Docs 而造成的各种问题，作者概不负责。手册作者无法确定手册内容是否会对读者身心健康产生不良影响。如果您未满 18 岁，或因阅读手册而产生不适，请立即停止阅读并咨询心理医生。

本书编委会欢迎接受您的指教。如果您对本书内容有任何问题、或建议，请联络我们：[falcary@foxmail.com](mailto:falcary@foxmail.com)）。我们并不保证回复每一封邮件，但是我们会认真接受并思考您的意见，并在后续版本中做出相应的改进。

本文协作地址是：[AI Lab of DUT](https://ujsosoymgz.feishu.cn/docx/LX8ldzcqCoB11GxCFDGcogFAnie?from=from_copylink)  

## 0.2  Docs 序言

**序言 1** 

撰写此 docs 的想法💡来源于 Dalian - Shenzhen 的航班上，当时觉得有必要对大学阶段做一个总结，然后就直接开始构思如何写这篇 docs 了。

本人于 2021 年的暑假误打误撞地选上了人工智能这个专业，当时的我近乎是抛弃了所有（我的所有好朋友几乎都选了其他专业，而且都搬走去了五舍）来到了这个我完全不熟悉的专业开始发展，刚开始我很迷茫和彷徨，因为我大一几乎没有接触过人工智能的任何东西，除了浅浅学会了 python，有着较高的绩点，其他比赛近乎一无所有。而大二阶段的我害怕落后于他人（特别是转专业过来的同学，真的很猛很优秀），基本上对自己做了很完善的规划，再加上我们是新的专业，没有像计算机、信通那样完善的学长学姐留下来的资源，所有考试基本上除了老师考前划重点其余的都是自己+同学们一起努力，所以我从那时起就开始下定决心，稳步前行。

撰写该 docs 的目的主要是为了让更多同学来了解大工 AI 的研究方向、学习方式和未来前景等等，旨在传递经验而非提供资源，存在较强的主观性，希望阅读者能够自行分辨并找到适合自己的路。

后续阶段，为了避免此文档具备”精英“效应，本人邀请了不同年级、不同成绩、不同专业、不同学院的朋友一同撰写，保证文档内容的详实性和专业性，很感谢他们对于本 docs 的贡献🎉，也很感谢磊哥、汤汤等等学长学姐和朋友们的帮助与支持，希望大工的 AI 和电类专业发展越来越好，也希望大家良性竞争、互帮互助，上岸梦校。

由于本文由多人协作，若内容侵犯到您的利益，烦请联系文末的联系方式删除，谢谢🙏如果你觉得本文对你有所帮助，请滑到文末帮忙点一个赞👍，谢谢捏～

**序言 2**

在大连理工大学的三年生活中，我目睹和经历了太多的荒谬，太多的错误，太多的茫然，太多的无奈，太多的失败，每个人成功的背后隐藏着日日夜夜的付出和折磨。自诩为天之骄子的高中毕业生，站在大学的门槛上，有时竟会显得像低龄儿童一样幼稚。年轻的同学们还为自己那充满无限可能的青春而沾沾自喜，却不曾意识到，一生仅此一张的白纸，绝不可以随意地涂抹。本书希望能为同学们树立正确的人生观和价值观，并在具体政策上，提供各种切实可行的建议，帮助同学里那一部分有志青年完善自我，实现内心的追求。回首四年大学时光，我一直保有一种强烈的对科学知识的虔诚。这份虔诚迫使我重新思考每天那本应“司空见惯”的生活，这份虔诚让我站出来，以我认为正确的方式贯彻自己的追求。

> *学会敬畏，学会谦卑，学会平和而执着、谦虚而无畏！*

在此，我与伙伴们把我们这三年和生活斗争的点点滴滴的经验和感悟记录下来，一方面，我希望我能为那些像我一样压抑中的灵魂尽一点义务。另一方面，也希望这本书本身，能成为推动各种不合理制度进步的一种动力。

现实总是令人遗憾的。我们当中太多人已经习惯于沿着那一成不变的“典型成功道路”前进：中考，高考，考研，出国......埋头赶路。走在前面的已然迷失，跟在后面的却还未开始思考。这不应该是一个国家、一个时代的精神。

这本书不是《逃课手册》或者《考前突击宝典》，更多的像是一本《经验汇总大全》。我希望帮助各位读者做到的，绝不是简单的拿高分、或者顺利毕业。我衷心希望希望这本书能够带给读者一些新鲜的思考，让同学们能看到人生道路上不同的风景，让整个专业的同学都是为了自己理想和目标而奋斗。至少在读过本书之后，各位读者应该能够有勇气、有智慧，去发现并挑战那些比上课、考高分、争奖学金更为重要的追求。

**⚠️ 注意：**

本文偏向于**电类或AI专业**的理解和解读，希望不同专业的同学可以从中获取自己所需的一部分信息。

## 03.这本书适合谁

任何有志于自学计算机和人工智能的朋友都可以参考这本书，如果你已经有了一定的计算机和人工智能基础，只是对某个特定的领域感兴趣，可以选择性地挑选你感兴趣的内容进行学习。当然，如果你是一个像我当年一样对计算机一无所知的小白，初入大学的校门，我希望这本书能成为你的攻略，让你花最少的时间掌握你所需要的知识和能力。某种程度上，这本书更像是一个根据我的体验来排序的课程搜索引擎，帮助大家足不出户，体验世界顶级名校的计算机和AI的优质课程。

当然，作为一个还未毕业的本科生，我深感自己没有能力也没有权利去宣扬一种学习方式，我只是希望这份资料能让那些同样有自学之心和毅力朋友可以少走些弯路，收获更丰富、更多样、更满足的学习体验。

同时，在本书的中还会分享关于大工电类专业历年的学习经验分享（包括考研、保研等）、也会有一些活动的简单介绍，旨在帮助萌新小朋友们尽快适应大学生活，希望能对有缘的你有所帮助。

## 04.你也想加入到贡献者的行列

一个人的力量终究是有限的，这本书也是我在繁重的科研之余熬夜抽空写出来的，难免有不够完善之处。另外，由于个人做的是系统方向，很多课程侧重系统领域，对于数学、理论计算机、高级算法相关的内容则相对少些。如果有大佬想在其他领域分享自己的自学经历与资源，可以直接在项目中发起 Pull Request，也欢迎和我邮件联系（[falcary@foxmail.com](mailto:falcary@foxmail.com)）。

## 05.特别鸣谢

特别感谢参与此docs写作的所有朋友们，感谢北大信科某位伟大的学长的开源分享，也真诚地感谢所有将课程资源无偿开源的各位教授们。这些课程倾注了他们数十年教学生涯的积淀和心血，他们却选择无私地让所有人享受到如此高质量的CS+AI教育。没有他们，我的大学生活不会这样充实而快乐。

## 请作者喝杯下午茶

本书的内容是完全开源免费的，如果你觉得该项目对你真的有帮助，可以给仓库点个 star 或者请作者喝一杯下午茶。

![Image title](./images/PAYMENT.png)

------

<script src="https://giscus.app/client.js"
        data-repo="AnonymousDUTAI/SREKCARC-IA-TUD"
        data-repo-id="R_kgDOKG3dKg"
        data-category="General"
        data-category-id="DIC_kwDOKG3dKs4CYmFw"
        data-mapping="pathname"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="top"
        data-theme="preferred_color_scheme"
        data-lang="zh-CN"
        data-loading="lazy"
        crossorigin="anonymous"
        async>
</script>

<script>
    var palette = __get("__palette")
    if (palette && typeof palette.color === "object") {
        if (palette.color.scheme === "slate") {
            const giscus = document.querySelector("script[src*=giscus]")
            giscus.setAttribute("data-theme", "dark_protanopia")
        }
    }

    document.addEventListener("DOMContentLoaded", function () {
        const ref = document.querySelector("[data-md-component=palette]")
        ref.addEventListener("change", function () {
            var palette = __get("__palette")
            if (palette && typeof palette.color === "object") {
                const theme = palette.color.scheme === "slate" ? "dark_protanopia" : "light_protanopia"
                const frame = document.querySelector(".giscus-frame")
                frame.contentWindow.postMessage({
                    giscus: { setConfig: { theme } }
                }, "https://giscus.app")
            }
        })
    })
</script>

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-WKNQN4V76J"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-WKNQN4V76J');
</script>