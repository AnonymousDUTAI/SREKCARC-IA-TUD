# TODO LIST

## ❌未完成

1. 经验分享部分 80%
    - 保研 和 考研经验分享（科创保研、行政保研；考外校的经验贴）
    - 学在大工部分：文体活动、社会工作的一些内容补充
    - 活在大工部分：政策讲解（奖学金+保研）
2. 自学部分 90%
    - 课程建议搜集：计算机视觉、自然语言处理、类脑、机器人

3. 资料分享部分 60%
    - 加入大三的资料库到文档中 完成度 20%
    - 关于课程的评价标准建立（打算以评分的角度进行，如课程重要性、讲课深度、考试难度等方面进行评定）

4. 招募管理人员（目前💫 1/5）
    - 欢迎有责任心、热心 or 熟练掌握前端开发 or 熟悉git协作 的朋友联系[作者](mailto:falcary@foxmail.com)



## 奇怪的讨论区

   > 此部分欢迎大家吐槽一些奇奇怪怪的课，或者帮助自己组里的老师打打广告啥的，同时大家也可以在此分享自己学习经验或者方法，如果点赞数高的话我会考虑将其放入docs中，届时会通知到个人。

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