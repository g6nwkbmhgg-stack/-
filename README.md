
# -
个人网站
<!doctype html>
<html lang="zh-CN">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>视觉设计师作品集 | 3D / AI Visual Portfolio</title>
    <meta
      name="description"
      content="视觉设计师（3D/AI方向）个人作品集，展示 C4D 静态渲染、C4D 动态渲染和 AI 视觉创作。"
    />
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <header class="site-header" aria-label="主导航">
      <a class="brand-mark" href="#top" aria-label="返回首页">3D/AI</a>
      <nav class="nav-links" aria-label="页面导航">
        <a href="#works">作品</a>
        <a href="#secondary">交付</a>
        <a href="#about">关于</a>
        <a href="#contact">联系</a>
      </nav>
    </header>

    <main id="top">
      <section class="hero" aria-labelledby="hero-title">
        <div class="hero-stage" aria-hidden="true">
          <div class="hero-noise"></div>
          <img class="stage-img stage-main" src="./assets/c4d-static/mouse.png" alt="" />
          <img class="stage-img stage-a" src="./assets/ai-visual/ai-05.png" alt="" />
          <img class="stage-img stage-b" src="./assets/c4d-static/perfume.png" alt="" />
          <img class="stage-img stage-c" src="./assets/ai-visual/ai-06.png" alt="" />
          <div class="hero-light-sweep"></div>
          <div class="hero-orbit orbit-one"></div>
          <div class="hero-orbit orbit-two"></div>
        </div>
        <div class="hero-media" aria-label="首页代表作品预览">
          <img src="./assets/c4d-static/mouse.png" alt="C4D 鼠标产品渲染代表作品" />
          <div class="hero-media-grid">
            <img src="./assets/ai-visual/ai-05.png" alt="AI 横版视觉生成作品" />
            <img src="./assets/ai-visual/ai-06.png" alt="AI 横版视觉生成作品" />
          </div>
        </div>

        <div class="hero-copy">
          <p class="eyebrow">Liu Zhiwei / Visual Designer</p>
          <h1 id="hero-title">
            <span>VISUAL</span>
            <span>DESIGN</span>
            <span>C4D + AI</span>
          </h1>
          <p class="hero-role">视觉设计师 / 3D 渲染 / AI 视觉生成</p>
          <p class="hero-lead">
            聚焦 C4D 产品渲染、动态视觉和 AI 图像生成，把工具表现力转化为完整、清晰、有商业质感的视觉作品。
          </p>
          <div class="hero-metrics" aria-label="作品方向">
            <span>C4D RENDER</span>
            <span>MOTION</span>
            <span>AI VISUAL</span>
          </div>
          <div class="hero-actions">
            <a class="button primary" href="#works">查看作品</a>
            <a class="button secondary" href="#contact">联系我</a>
          </div>
        </div>
      </section>

      <section class="ticker" aria-label="能力关键词">
        <div class="ticker-track">
          <span>C4D 渲染</span>
          <span>16:9 作品展示</span>
          <span>动态视觉</span>
          <span>AI 视觉生成</span>
          <span>产品视觉</span>
          <span>C4D 渲染</span>
          <span>16:9 作品展示</span>
          <span>动态视觉</span>
          <span>AI 视觉生成</span>
          <span>产品视觉</span>
        </div>
      </section>

      <section class="works-section" id="works" aria-labelledby="works-title">
        <div class="section-heading reveal">
          <p class="eyebrow">Core Works</p>
          <h2 id="works-title">作品展示</h2>
          <p>
            围绕 C4D 静态渲染、C4D 动态渲染与 AI 视觉三类能力展开。
          </p>
        </div>

        <div class="work-switcher reveal" role="tablist" aria-label="核心作品分组">
          <a class="switch-button active" href="#c4d-static" role="tab" aria-selected="true">
            C4D静态渲染
          </a>
          <a class="switch-button" href="#c4d-motion" role="tab" aria-selected="false">
            C4D动态渲染
          </a>
          <a class="switch-button" href="#ai-visual" role="tab" aria-selected="false">
            AI视觉
          </a>
        </div>

        <div class="gallery-shell">
          <article class="work-panel active" id="c4d-static" data-panel="c4d-static">
            <div class="panel-copy">
              <p class="panel-index">01</p>
              <h3>C4D静态渲染</h3>
              <p>覆盖美妆、数码、饮品、家居、鞋履等多种产品表达。</p>
              <div class="tags">
                <span>C4D</span>
                <span>产品渲染</span>
                <span>材质表现</span>
                <span>商业视觉</span>
              </div>
            </div>
            <div class="media-grid" aria-label="C4D静态渲染作品网格">
              <figure class="media-card feature">
                <img src="./assets/c4d-static/perfume.png" alt="香水产品静态渲染" />
                <figcaption>香水 / 场景与透明材质</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/c4d-static/hero-product.png" alt="产品主视觉静态渲染" />
                <figcaption>产品主视觉 / 光影构图</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/c4d-static/phone.png" alt="手机产品静态渲染" />
                <figcaption>手机 / 数码产品</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/c4d-static/drink.png" alt="饮品产品静态渲染" />
                <figcaption>饮品 / 商业场景</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/c4d-static/mouse.png" alt="鼠标产品静态渲染" />
                <figcaption>鼠标 / 工业产品</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/c4d-static/shelf.png" alt="储物架产品静态渲染" />
                <figcaption>储物架 / 家居产品</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/c4d-static/earbuds.png" alt="耳机产品静态渲染" />
                <figcaption>耳机 / 电子产品</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/c4d-static/zhiben.png" alt="逐本产品静态渲染" />
                <figcaption>护肤产品 / 品牌质感</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/c4d-static/shoes.jpg" alt="鞋子产品静态渲染" />
                <figcaption>鞋履 / 运动产品</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/c4d-static/speaker.png" alt="音响产品静态渲染" />
                <figcaption>音响 / 硬件产品</figcaption>
              </figure>
            </div>
          </article>

          <article class="work-panel" id="c4d-motion" data-panel="c4d-motion">
            <div class="panel-copy">
              <p class="panel-index">02</p>
              <h3>C4D动态渲染</h3>
              <p>使用 C4D 渲染 + 剪辑完成。</p>
              <div class="tags">
                <span>Motion</span>
                <span>16:9 Video</span>
                <span>产品动画</span>
                <span>镜头节奏</span>
              </div>
            </div>
            <div class="media-grid video-grid" aria-label="C4D动态渲染视频网格">
              <figure class="media-card video-card">
                <video src="./assets/c4d-motion/motion-02.mp4" muted loop playsinline controls preload="metadata"></video>
                <figcaption>手机</figcaption>
              </figure>
              <figure class="media-card video-card">
                <video src="./assets/c4d-motion/motion-earbuds.mp4" muted loop playsinline controls preload="metadata"></video>
                <figcaption>蓝牙耳机</figcaption>
              </figure>
            </div>
          </article>

          <article class="work-panel" id="ai-visual" data-panel="ai-visual">
            <div class="panel-copy">
              <p class="panel-index">03</p>
              <h3>AI视觉</h3>
              <p>通过 AI 图像生成完成多方向视觉探索，聚焦概念设定、场景氛围与风格筛选。</p>
              <div class="tags">
                <span>AI生成</span>
                <span>概念视觉</span>
                <span>风格探索</span>
                <span>图像筛选</span>
              </div>
            </div>
            <div class="media-grid" aria-label="AI视觉作品网格">
              <figure class="media-card feature">
                <img src="./assets/ai-visual/ai-01.png" alt="AI 视觉概念作品一" />
                <figcaption>概念视觉 / 场景塑造</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/ai-visual/ai-02.png" alt="AI 视觉概念作品二" />
                <figcaption>风格探索 / 视觉提案</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/ai-visual/ai-03.png" alt="AI 视觉概念作品三" />
                <figcaption>氛围生成 / 叙事画面</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/ai-visual/ai-04.png" alt="AI 视觉概念作品四" />
                <figcaption>图像生成 / 方向筛选</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/ai-visual/ai-05.png" alt="AI 视觉概念作品五" />
                <figcaption>视觉实验 / 画面构成</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/ai-visual/ai-06.png" alt="AI 视觉概念作品六" />
                <figcaption>系列探索 / 风格一致性</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/ai-visual/ai-07.png" alt="AI 视觉概念作品七" />
                <figcaption>场景生成 / 光影控制</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/ai-visual/ai-08.png" alt="AI 视觉概念作品八" />
                <figcaption>创意方向 / 图像提案</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/ai-visual/ai-09.png" alt="AI 视觉概念作品九" />
                <figcaption>氛围视觉 / 情绪表达</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/ai-visual/ai-10.png" alt="AI 视觉概念作品十" />
                <figcaption>视觉延展 / 方向测试</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/ai-visual/ai-11.png" alt="AI 视觉概念作品十一" />
                <figcaption>生成图像 / 商业化筛选</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/ai-visual/ai-12.png" alt="AI 视觉概念作品十二" />
                <figcaption>概念画面 / 风格沉淀</figcaption>
              </figure>
            </div>
          </article>
        </div>
      </section>

      <section class="secondary-section" id="secondary" aria-labelledby="secondary-title">
        <div class="section-heading reveal">
          <p class="eyebrow">Applied Projects</p>
          <h2 id="secondary-title">交付项目</h2>
        </div>
        <div class="landing-grid">
          <article class="landing-card reveal">
            <div class="landing-card-heading">
              <p>Project Stills</p>
              <h3>角色IP</h3>
              <span>皮克斯动画项目 / 角色设定 / 画面延展</span>
            </div>
            <div class="landing-photo-carousel">
              <figure class="media-card">
                <img src="./assets/secondary/pixar-felix.png" alt="皮克斯动画项目角色费利克斯" />
                <figcaption>费利克斯 / 动画角色视觉</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/secondary/pixar-para.png" alt="皮克斯动画项目角色帕拉" />
                <figcaption>帕拉 / 角色视觉探索</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/secondary/pixar-qiqi.png" alt="皮克斯动画项目角色琪琪" />
                <figcaption>琪琪 / 动画角色表达</figcaption>
              </figure>
              <figure class="media-card">
                <img src="./assets/secondary/pixar-lenny.png" alt="皮克斯动画项目角色莱尼" />
                <figcaption>莱尼 / 角色设定延展</figcaption>
              </figure>
            </div>
          </article>
          <article class="landing-card reveal">
            <div class="landing-card-heading">
              <p>Project Film</p>
              <h3>实拍+AI</h3>
              <span>亚马逊项目 / 灯具产品 / 场景展示</span>
            </div>
            <div class="landing-video-carousel">
              <figure class="media-card landing-video-card video-card">
                <video src="./assets/secondary/amazon-egg-light.mp4" muted loop playsinline controls preload="metadata"></video>
                <figcaption>亚马逊项目 / 蛋型灯展示</figcaption>
              </figure>
              <figure class="media-card landing-video-card video-card">
                <video src="./assets/secondary/amazon-night-light.mp4" muted loop playsinline controls preload="metadata"></video>
                <figcaption>亚马逊项目 / 夜灯产品动态视觉</figcaption>
              </figure>
              <figure class="media-card landing-video-card video-card">
                <video src="./assets/secondary/amazon-square-night-light.mp4" muted loop playsinline controls preload="metadata"></video>
                <figcaption>亚马逊项目 / 小夜灯产品展示</figcaption>
              </figure>
              <figure class="media-card landing-video-card video-card">
                <video src="./assets/secondary/amazon-outdoor-wall-light.mp4" muted loop playsinline controls preload="metadata"></video>
                <figcaption>亚马逊项目 / 户外壁灯展示</figcaption>
              </figure>
              <figure class="media-card landing-video-card video-card">
                <video src="./assets/secondary/amazon-ceiling-install.mp4" muted loop playsinline controls preload="metadata"></video>
                <figcaption>亚马逊项目 / 吸顶灯安装展示</figcaption>
              </figure>
              <figure class="media-card landing-video-card video-card">
                <video src="./assets/secondary/amazon-camping-light.mp4" muted loop playsinline controls preload="metadata"></video>
                <figcaption>亚马逊项目 / 露营灯产品展示</figcaption>
              </figure>
            </div>
          </article>
        </div>
      </section>

      <section class="about-contact" id="about" aria-labelledby="about-title">
        <div class="about-block reveal">
          <p class="eyebrow">About</p>
          <h2 id="about-title">刘志伟</h2>
          <p>
            我是一名专注于 3D 视觉与 AI 创意方向的视觉设计师，擅长围绕产品特性、核心卖点与功能多样性，进行视觉呈现、动态渲染及 AI 辅助创意探索。我能够将工具的表现力转化为清晰、完整且具备交付价值的视觉作品，帮助产品以更直观、更高级的方式被看见。
          </p>
          <div class="skill-strip" aria-label="掌握工具">
            <span>C4D建模渲染</span>
            <span>主流AI模型运用</span>
            <span>摄影</span>
            <span>PS</span>
            <span>剪映</span>
            <span>AI工作流搭建</span>
          </div>
        </div>

        <div class="contact-block reveal" id="contact">
          <p class="eyebrow">Contact</p>
          <h2>联系我</h2>
          <p>欢迎沟通视觉合作与3D/AI方向视觉相关岗位机会。</p>
          <div class="contact-actions">
            <a class="button primary" href="tel:18320468455">电话联系</a>
            <a class="button secondary" href="./resume.pdf" download>下载简历</a>
          </div>
          <p class="contact-note">电话 / 微信：18320468455</p>
        </div>
      </section>
    </main>

    <footer class="site-footer">
      <span>Visual Portfolio / 3D + AI</span>
      <a href="#top">回到顶部</a>
    </footer>

    <div class="lightbox" id="lightbox" role="dialog" aria-modal="true" aria-label="作品大图预览" hidden>
      <button class="lightbox-close" type="button" aria-label="关闭大图">Close</button>
      <figure class="lightbox-content">
        <img class="lightbox-image" src="" alt="" />
        <figcaption class="lightbox-caption"></figcaption>
      </figure>
    </div>

    <script src="./script.js"></script>
  </body>
</html>

const switchButtons = document.querySelectorAll(".switch-button");

switchButtons.forEach((button) => {
  button.addEventListener("click", () => {
    switchButtons.forEach((item) => {
      const isActive = item === button;
      item.classList.toggle("active", isActive);
      item.setAttribute("aria-selected", String(isActive));
    });
  });
});

document.querySelectorAll(".immersive-gallery").forEach((gallery) => {
  let isDown = false;
  let startX = 0;
  let scrollLeft = 0;

  gallery.addEventListener("pointerdown", (event) => {
    isDown = true;
    startX = event.pageX - gallery.offsetLeft;
    scrollLeft = gallery.scrollLeft;
    gallery.classList.add("dragging");
    gallery.setPointerCapture(event.pointerId);
  });

  gallery.addEventListener("pointermove", (event) => {
    if (!isDown) return;
    const x = event.pageX - gallery.offsetLeft;
    gallery.scrollLeft = scrollLeft - (x - startX) * 1.2;
  });

  const release = () => {
    isDown = false;
    gallery.classList.remove("dragging");
  };

  gallery.addEventListener("pointerup", release);
  gallery.addEventListener("pointercancel", release);
  gallery.addEventListener("pointerleave", release);
});

document.querySelectorAll(".video-card video, .secondary-work video").forEach((video) => {
  const parent = video.closest(".video-card, .secondary-work");

  parent.addEventListener("mouseenter", () => {
    video.play().catch(() => {});
  });

  parent.addEventListener("mouseleave", () => {
    video.pause();
  });

  parent.addEventListener("click", () => {
    if (video.paused) {
      video.play().catch(() => {});
    } else {
      video.pause();
    }
  });
});

const revealObserver = new IntersectionObserver(
  (entries) => {
    entries.forEach((entry) => {
      if (entry.isIntersecting) {
        entry.target.classList.add("visible");
        revealObserver.unobserve(entry.target);
      }
    });
  },
  { threshold: 0.16 }
);

document.querySelectorAll(".reveal").forEach((item) => revealObserver.observe(item));

document.querySelectorAll(".work-panel .media-grid:not(.video-grid), .landing-photo-carousel, .landing-video-carousel").forEach((grid) => {
  const cards = Array.from(grid.querySelectorAll(".media-card"));
  if (cards.length < 2) return;

  grid.classList.add("carousel-enabled");
  cards[0].classList.add("carousel-active");

  const controls = document.createElement("div");
  controls.className = "carousel-controls";
  controls.innerHTML = `
    <button class="carousel-button carousel-prev" type="button" aria-label="上一张">‹</button>
    <div class="carousel-dots" aria-label="轮播分页"></div>
    <button class="carousel-button carousel-next" type="button" aria-label="下一张">›</button>
  `;

  const status = document.createElement("div");
  status.className = "carousel-status";
  grid.after(status);
  grid.after(controls);

  const dotsWrap = controls.querySelector(".carousel-dots");
  const dots = cards.map((_, index) => {
    const dot = document.createElement("button");
    dot.className = "carousel-dot";
    dot.type = "button";
    dot.setAttribute("aria-label", `查看第 ${index + 1} 张`);
    dotsWrap.append(dot);
    return dot;
  });

  let activeIndex = 0;
  let timer;

  const showSlide = (index) => {
    cards[activeIndex]?.querySelectorAll("video").forEach((video) => {
      video.pause();
    });

    activeIndex = (index + cards.length) % cards.length;

    cards.forEach((card, cardIndex) => {
      card.classList.toggle("carousel-active", cardIndex === activeIndex);
    });

    dots.forEach((dot, dotIndex) => {
      dot.classList.toggle("active", dotIndex === activeIndex);
      dot.setAttribute("aria-current", dotIndex === activeIndex ? "true" : "false");
    });

    status.textContent = `${activeIndex + 1} / ${cards.length}`;
  };

  const start = () => {
    window.clearInterval(timer);
    timer = window.setInterval(() => showSlide(activeIndex + 1), grid.classList.contains("landing-video-carousel") ? 7000 : 3600);
  };

  const stop = () => {
    window.clearInterval(timer);
  };

  controls.querySelector(".carousel-prev").addEventListener("click", () => {
    showSlide(activeIndex - 1);
    start();
  });

  controls.querySelector(".carousel-next").addEventListener("click", () => {
    showSlide(activeIndex + 1);
    start();
  });

  dots.forEach((dot, dotIndex) => {
    dot.addEventListener("click", () => {
      showSlide(dotIndex);
      start();
    });
  });

  grid.addEventListener("mouseenter", stop);
  grid.addEventListener("mouseleave", start);
  controls.addEventListener("mouseenter", stop);
  controls.addEventListener("mouseleave", start);

  showSlide(0);
  start();
});

const lightbox = document.querySelector("#lightbox");
const lightboxImage = document.querySelector(".lightbox-image");
const lightboxCaption = document.querySelector(".lightbox-caption");
const lightboxClose = document.querySelector(".lightbox-close");

const closeLightbox = () => {
  if (!lightbox) return;
  lightbox.hidden = true;
  document.body.classList.remove("lightbox-open");
  lightboxImage.removeAttribute("src");
  lightboxImage.alt = "";
  lightboxCaption.textContent = "";
};

document.querySelectorAll(".media-card img, .hero-media img, .secondary-work img").forEach((image) => {
  image.addEventListener("click", () => {
    const caption = image.closest("figure")?.querySelector("figcaption")?.innerText || image.alt || "作品预览";

    lightboxImage.src = image.currentSrc || image.src;
    lightboxImage.alt = image.alt || caption;
    lightboxCaption.textContent = caption;
    lightbox.hidden = false;
    document.body.classList.add("lightbox-open");
    lightboxClose.focus();
  });
});

lightboxClose?.addEventListener("click", closeLightbox);

lightbox?.addEventListener("click", (event) => {
  if (event.target === lightbox) {
    closeLightbox();
  }
});

document.addEventListener("keydown", (event) => {
  if (event.key === "Escape" && lightbox && !lightbox.hidden) {
    closeLightbox();
  }
});

const heroStage = document.querySelector(".hero-stage");

if (heroStage) {
  heroStage.addEventListener("pointermove", (event) => {
    const rect = heroStage.getBoundingClientRect();
    const x = (event.clientX - rect.left) / rect.width - 0.5;
    const y = (event.clientY - rect.top) / rect.height - 0.5;

    heroStage.querySelectorAll(".stage-image").forEach((image, index) => {
      const depth = (index + 1) * 12;
      image.style.translate = `${x * depth}px ${y * depth}px`;
    });
  });

  heroStage.addEventListener("pointerleave", () => {
    heroStage.querySelectorAll(".stage-image").forEach((image) => {
      image.style.translate = "0 0";
    });
  });
}

:root {
  color-scheme: dark;
  --ink: #f2f4f3;
  --muted: #8c9496;
  --soft: rgba(210, 220, 222, 0.07);
  --soft-strong: rgba(210, 220, 222, 0.13);
  --line: rgba(214, 225, 226, 0.16);
  --black: #050607;
  --acid: #c7e8ff;
  --cyan: #89d8ff;
  --coral: #d7192c;
  --max: 1240px;
}

* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  min-width: 320px;
  overflow-x: hidden;
  background:
    linear-gradient(rgba(214, 225, 226, 0.025) 1px, transparent 1px),
    linear-gradient(90deg, rgba(214, 225, 226, 0.02) 1px, transparent 1px),
    radial-gradient(circle at 72% 18%, rgba(130, 175, 198, 0.12), transparent 38rem),
    radial-gradient(circle at 50% 100%, rgba(55, 70, 76, 0.24), transparent 34rem),
    #050607;
  background-size: 42px 42px, 42px 42px, auto, auto, auto;
  color: var(--ink);
  font-family:
    "Inter", "PingFang SC", "Microsoft YaHei", "Helvetica Neue", Arial,
    sans-serif;
  line-height: 1.5;
}

img,
video {
  display: block;
  max-width: 100%;
}

a {
  color: inherit;
  text-decoration: none;
}

button {
  font: inherit;
}

.site-header {
  position: fixed;
  top: 0;
  left: 0;
  z-index: 30;
  display: flex;
  width: 100%;
  align-items: center;
  justify-content: space-between;
  padding: 18px clamp(18px, 4vw, 54px);
  background: linear-gradient(180deg, rgba(7, 7, 6, 0.9), rgba(7, 7, 6, 0));
  pointer-events: none;
}

.brand-mark,
.nav-links {
  pointer-events: auto;
}

.brand-mark {
  display: inline-flex;
  min-width: 68px;
  min-height: 42px;
  align-items: center;
  justify-content: center;
  border: 1px solid var(--line);
  background: rgba(5, 6, 7, 0.72);
  color: #f2f4f3;
  font-size: 13px;
  font-weight: 950;
}

.nav-links {
  display: flex;
  gap: 6px;
  padding: 6px;
  border: 1px solid var(--line);
  background: rgba(5, 6, 7, 0.64);
  backdrop-filter: blur(16px);
}

.nav-links a {
  min-width: 52px;
  padding: 8px 12px;
  color: var(--muted);
  font-size: 13px;
  text-align: center;
}

.nav-links a:hover,
.nav-links a:focus-visible {
  background: var(--soft-strong);
  color: var(--ink);
  outline: 0;
}

.hero {
  position: relative;
  overflow: hidden;
  display: grid;
  min-height: 100svh;
  grid-template-columns: 1fr;
  align-items: end;
  padding: 92px clamp(20px, 5vw, 70px) 72px;
  isolation: isolate;
}

.hero::before,
.hero::after {
  position: absolute;
  pointer-events: none;
  content: "";
}

.hero::before {
  inset: -2%;
  z-index: -3;
  background:
    linear-gradient(90deg, rgba(1, 2, 3, 0.94) 0 29%, rgba(1, 2, 3, 0.42) 48%, rgba(1, 2, 3, 0.06) 72%, rgba(1, 2, 3, 0.55) 100%),
    linear-gradient(180deg, rgba(0, 0, 0, 0.56), transparent 22%, transparent 66%, rgba(0, 0, 0, 0.74)),
    url("./assets/hero-hi-bg.png");
  background-position: center;
  background-size: cover;
  filter: saturate(0.94) contrast(1.06) brightness(0.94);
  transform: scale(1.02);
  animation: hero-bg-breathe 12s ease-in-out infinite alternate;
}

.hero::after {
  inset: -18%;
  z-index: -1;
  background:
    linear-gradient(105deg, transparent 0 36%, rgba(225, 244, 255, 0.1) 44%, rgba(225, 244, 255, 0.02) 54%, transparent 64%),
    repeating-linear-gradient(90deg, transparent 0 34px, rgba(214, 225, 226, 0.035) 34px 35px),
    repeating-linear-gradient(0deg, rgba(255, 255, 255, 0.016) 0 1px, transparent 1px 6px);
  opacity: 0.72;
  transform: rotate(-6deg);
  animation: hero-scan 7s cubic-bezier(0.5, 0, 0.2, 1) infinite alternate;
}

.hero-stage {
  position: absolute;
  inset: 0;
  z-index: -2;
  overflow: hidden;
  pointer-events: none;
}

.hero-stage::before,
.hero-stage::after {
  position: absolute;
  pointer-events: none;
  content: "";
}

.hero-stage::before {
  left: clamp(20px, 5vw, 70px);
  right: clamp(20px, 5vw, 70px);
  bottom: 8.5vh;
  height: 1px;
  background: linear-gradient(90deg, rgba(242, 244, 243, 0.1), rgba(242, 244, 243, 0.74), rgba(131, 204, 255, 0.18), transparent);
  opacity: 0.78;
  animation: hero-line-pulse 4.2s ease-in-out infinite;
}

.hero-stage::after {
  right: 12vw;
  bottom: 8vh;
  width: min(42vw, 680px);
  aspect-ratio: 1 / 0.58;
  background:
    radial-gradient(ellipse at 52% 54%, rgba(188, 229, 255, 0.16), transparent 54%),
    linear-gradient(90deg, transparent, rgba(220, 242, 255, 0.08), transparent);
  filter: blur(22px);
  opacity: 0.55;
  transform: rotate(-7deg);
  animation: hero-ambient-glow 6.8s ease-in-out infinite alternate;
}

.hero-noise {
  position: absolute;
  inset: 0;
  background:
    linear-gradient(180deg, rgba(255, 255, 255, 0.035), transparent 34%),
    repeating-linear-gradient(0deg, rgba(255, 255, 255, 0.028) 0 1px, transparent 1px 5px);
  opacity: 0.28;
  mix-blend-mode: screen;
}

.hero-light-sweep {
  position: absolute;
  top: 43%;
  right: -12vw;
  width: 78vw;
  height: 13vh;
  background: linear-gradient(90deg, transparent, rgba(226, 245, 255, 0.16), rgba(226, 245, 255, 0.04), transparent);
  filter: blur(20px);
  opacity: 0.42;
  transform: rotate(-6deg);
  animation: hero-light-sweep 6.4s ease-in-out infinite;
}

.stage-img {
  display: none;
  position: absolute;
  border: 1px solid rgba(214, 225, 226, 0.2);
  background: #080a0b;
  box-shadow: 0 44px 160px rgba(0, 0, 0, 0.86);
  object-fit: cover;
  filter: saturate(0.78) contrast(1.14) brightness(0.88);
}

.stage-main {
  right: clamp(-160px, -4vw, -42px);
  top: 24vh;
  width: min(62vw, 980px);
  aspect-ratio: 16 / 9;
  clip-path: polygon(17% 0, 100% 5%, 86% 100%, 0 88%);
  opacity: 0.96;
  transform: rotate(-8deg);
  animation: hero-float-main 8s ease-in-out infinite;
  mix-blend-mode: normal;
}

.stage-a {
  top: clamp(82px, 10vh, 128px);
  left: clamp(58px, 6vw, 120px);
  width: min(22vw, 340px);
  aspect-ratio: 16 / 9;
  clip-path: polygon(0 7%, 94% 0, 100% 82%, 8% 100%);
  opacity: 0.58;
  transform: rotate(6deg);
  animation: hero-float-a 6.6s ease-in-out infinite;
}

.stage-b {
  right: min(42vw, 620px);
  bottom: clamp(86px, 12vh, 132px);
  width: min(22vw, 330px);
  aspect-ratio: 16 / 9;
  clip-path: polygon(12% 0, 100% 12%, 88% 100%, 0 86%);
  opacity: 0.68;
  transform: rotate(-12deg);
  animation: hero-float-b 7.4s ease-in-out infinite;
}

.stage-c {
  top: clamp(66px, 8vh, 104px);
  right: clamp(44px, 6vw, 110px);
  width: min(17vw, 280px);
  aspect-ratio: 16 / 9;
  clip-path: polygon(0 0, 100% 16%, 86% 100%, 10% 88%);
  opacity: 0.42;
  transform: rotate(13deg);
  animation: hero-float-c 6.9s ease-in-out infinite;
}

.hero-orbit {
  position: absolute;
  opacity: 0;
}

.hero-media {
  position: relative;
  display: none;
  align-content: center;
  gap: 14px;
}

.hero-media > img {
  width: 100%;
  aspect-ratio: 16 / 9;
  border: 1px solid rgba(215, 255, 53, 0.36);
  background: #111;
  box-shadow: 0 34px 120px rgba(0, 0, 0, 0.58);
  object-fit: cover;
}

.hero-media-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 14px;
}

.hero-media-grid img {
  width: 100%;
  aspect-ratio: 16 / 9;
  border: 1px solid var(--line);
  background: #111;
  object-fit: cover;
}

.hero-copy {
  position: relative;
  z-index: 2;
  display: grid;
  max-width: min(56vw, 920px);
  padding-bottom: 0;
  grid-column: 1 / -1;
  align-self: center;
  padding-top: 0;
  gap: 12px;
  animation: hero-copy-in 920ms cubic-bezier(0.16, 0.84, 0.22, 1) both;
}

.hero-copy::before {
  width: 34px;
  height: 1px;
  background: rgba(230, 245, 255, 0.72);
  content: "";
}

.eyebrow {
  margin: 0;
  color: rgba(242, 244, 243, 0.78);
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 0.16em;
  text-transform: uppercase;
}

h1,
h2,
h3,
p {
  margin-top: 0;
}

h1 {
  max-width: min(100%, 920px);
  margin: 12px 0 0;
  display: grid;
  gap: 0;
  color: rgba(242, 244, 243, 0.95);
  font-size: clamp(86px, 8.8vw, 164px);
  font-weight: 200;
  line-height: 0.74;
  letter-spacing: 0;
  text-transform: uppercase;
  text-shadow:
    0 0 24px rgba(199, 232, 255, 0.16),
    0 22px 80px rgba(0, 0, 0, 0.9);
}

h1 span {
  display: block;
  width: max-content;
  white-space: nowrap;
}

h1 span:nth-child(2) {
  position: relative;
  width: max-content;
  color: rgba(199, 232, 255, 0.82);
}

h1 span:last-child {
  color: rgba(242, 244, 243, 0.96);
  font-size: 0.66em;
  font-weight: 240;
  letter-spacing: 0.08em;
  -webkit-text-stroke: 0;
  text-shadow: 0 0 22px rgba(199, 232, 255, 0.2);
}

h1 span:nth-child(2)::after {
  position: absolute;
  left: 0;
  bottom: 0.1em;
  width: 100%;
  height: 1px;
  background: linear-gradient(90deg, rgba(199, 232, 255, 0.86), transparent);
  content: "";
}

.hero-role {
  margin: 10px 0 0;
  color: rgba(242, 244, 243, 0.78);
  font-size: clamp(15px, 1.08vw, 19px);
  font-weight: 500;
  letter-spacing: 0.16em;
}

.hero-lead {
  max-width: 500px;
  margin: 4px 0 0;
  color: rgba(242, 244, 243, 0.58);
  font-size: clamp(12px, 0.86vw, 14px);
  font-weight: 500;
  line-height: 1.85;
  text-wrap: balance;
}

.hero-metrics {
  display: flex;
  width: min(100%, 500px);
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 8px;
}

.hero-metrics span {
  border: 1px solid rgba(214, 225, 226, 0.18);
  background: rgba(5, 6, 7, 0.46);
  color: rgba(242, 244, 243, 0.76);
  padding: 6px 9px;
  font-size: 10px;
  font-weight: 800;
  letter-spacing: 0.08em;
  backdrop-filter: blur(12px);
}

.hero-actions,
.contact-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-top: 12px;
}

.button {
  display: inline-flex;
  min-height: 42px;
  align-items: center;
  justify-content: center;
  padding: 11px 18px;
  border: 1px solid var(--line);
  font-size: 12px;
  font-weight: 900;
  transition: transform 180ms ease, background 180ms ease;
}

.button:hover,
.button:focus-visible {
  transform: translateY(-2px);
  outline: 0;
}

.button.primary {
  border-color: rgba(242, 244, 243, 0.78);
  background: rgba(242, 244, 243, 0.9);
  color: #050607;
}

.button.secondary {
  background: rgba(5, 6, 7, 0.42);
  color: var(--ink);
}

.ticker {
  overflow: hidden;
  border-block: 1px solid var(--line);
  background: linear-gradient(90deg, rgba(214, 225, 226, 0.06), rgba(214, 225, 226, 0.16), rgba(214, 225, 226, 0.06));
  color: rgba(242, 244, 243, 0.72);
}

.ticker-track {
  display: flex;
  width: max-content;
  animation: ticker 24s linear infinite;
}

.ticker span {
  padding: 14px 28px;
  font-size: 15px;
  font-weight: 950;
  white-space: nowrap;
}

.works-section,
.secondary-section,
.about-contact {
  padding: clamp(58px, 8vw, 104px) clamp(20px, 5vw, 70px);
}

.section-heading,
.gallery-shell,
.work-switcher,
.secondary-grid,
.landing-grid {
  max-width: var(--max);
  margin-inline: auto;
}

.gallery-shell {
  opacity: 1;
  transform: none;
}

.work-panel[hidden] {
  display: none !important;
}

.section-heading {
  margin-bottom: 22px;
}

.section-heading h2,
.about-block h2,
.contact-block h2 {
  margin-bottom: 14px;
  font-size: clamp(34px, 5vw, 72px);
  line-height: 0.98;
}

.section-heading p:not(.eyebrow),
.about-block p,
.contact-block p {
  max-width: 740px;
  color: var(--muted);
  font-size: 17px;
}

.work-switcher {
  position: sticky;
  top: 82px;
  z-index: 10;
  display: flex;
  gap: 10px;
  overflow-x: auto;
  margin-bottom: 14px;
  padding: 8px;
  border: 1px solid var(--line);
  background: rgba(7, 7, 6, 0.78);
  backdrop-filter: blur(18px);
}

.switch-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-width: max-content;
  cursor: pointer;
  border: 1px solid var(--line);
  background: rgba(248, 246, 236, 0.05);
  color: var(--muted);
  padding: 12px 16px;
  font-weight: 900;
}

.switch-button.active,
.switch-button:hover,
.switch-button:focus-visible {
  border-color: rgba(215, 255, 53, 0.78);
  background: rgba(215, 255, 53, 0.18);
  color: var(--ink);
  outline: 0;
}

.work-panel {
  display: grid;
  gap: 14px;
  margin-bottom: clamp(42px, 7vw, 86px);
  scroll-margin-top: 96px;
}

.panel-copy {
  display: grid;
  grid-template-columns: 72px minmax(0, 1fr);
  gap: 20px;
  align-items: start;
  padding: 22px;
  border: 1px solid var(--line);
  background: rgba(248, 246, 236, 0.06);
}

.panel-index {
  margin: 0;
  color: var(--coral);
  font-size: 34px;
  font-weight: 950;
  line-height: 1;
}

.panel-copy h3 {
  margin-bottom: 10px;
  font-size: clamp(26px, 3vw, 40px);
  line-height: 1;
}

.panel-copy p:not(.panel-index) {
  grid-column: 2;
  max-width: 760px;
  color: var(--muted);
}

.tags,
.skill-strip {
  display: flex;
  flex-wrap: wrap;
  gap: 7px;
  margin-top: 18px;
}

.panel-copy .tags {
  grid-column: 2;
  margin-top: 0;
}

.tags span,
.skill-strip span {
  border: 1px solid var(--line);
  background: rgba(7, 7, 6, 0.44);
  color: var(--ink);
  padding: 7px 9px;
  font-size: 11px;
  font-weight: 850;
}

.skill-strip span:nth-child(1) {
  border-color: rgba(126, 210, 255, 0.42);
  background: rgba(29, 102, 142, 0.34);
}

.skill-strip span:nth-child(2) {
  border-color: rgba(168, 232, 255, 0.38);
  background: rgba(70, 116, 138, 0.3);
}

.skill-strip span:nth-child(3) {
  border-color: rgba(194, 178, 255, 0.38);
  background: rgba(88, 72, 142, 0.3);
}

.skill-strip span:nth-child(4) {
  border-color: rgba(118, 166, 255, 0.42);
  background: rgba(38, 72, 138, 0.32);
}

.skill-strip span:nth-child(5) {
  border-color: rgba(124, 238, 210, 0.36);
  background: rgba(36, 112, 98, 0.3);
}

.skill-strip span:nth-child(6) {
  border-color: rgba(235, 205, 132, 0.38);
  background: rgba(132, 98, 34, 0.28);
}

.media-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 18px;
}

.carousel-enabled {
  position: relative;
  display: block;
}

.carousel-enabled .media-card {
  display: none;
}

.carousel-enabled .media-card.carousel-active {
  display: block;
}

.carousel-enabled:not(.landing-video-carousel) .media-card.carousel-active {
  animation: carousel-card-in 720ms cubic-bezier(0.2, 0.78, 0.18, 1) both;
}

.carousel-enabled:not(.landing-video-carousel) .media-card.carousel-active img {
  animation: carousel-image-in 900ms cubic-bezier(0.2, 0.78, 0.18, 1) both;
  will-change: transform, filter;
}

.carousel-enabled:not(.landing-video-carousel) .media-card.carousel-active::after {
  position: absolute;
  inset: 0;
  pointer-events: none;
  background:
    linear-gradient(105deg, transparent 8%, rgba(215, 255, 53, 0.16) 32%, transparent 58%),
    linear-gradient(180deg, transparent 62%, rgba(0, 0, 0, 0.32));
  content: "";
  mix-blend-mode: screen;
  opacity: 0;
  animation: carousel-scan 900ms ease-out both;
}

.carousel-enabled .media-card.feature,
.carousel-enabled .media-card {
  grid-column: auto;
}

.carousel-controls {
  display: grid;
  grid-template-columns: auto 1fr auto;
  gap: 12px;
  align-items: center;
  margin-top: 12px;
}

.carousel-button {
  min-width: 44px;
  min-height: 38px;
  cursor: pointer;
  border: 1px solid var(--line);
  background: rgba(248, 246, 236, 0.06);
  color: var(--ink);
  font-size: 18px;
  font-weight: 950;
}

.carousel-button:hover,
.carousel-button:focus-visible {
  border-color: rgba(215, 255, 53, 0.78);
  background: rgba(215, 255, 53, 0.16);
  outline: 0;
}

.carousel-dots {
  display: flex;
  justify-content: center;
  gap: 7px;
  overflow-x: auto;
  padding: 6px 0;
}

.carousel-dot {
  width: 8px;
  height: 8px;
  flex: 0 0 auto;
  cursor: pointer;
  border: 0;
  border-radius: 999px;
  background: rgba(248, 246, 236, 0.34);
  padding: 0;
}

.carousel-dot.active {
  width: 24px;
  background: var(--acid);
}

.carousel-status {
  margin-top: 8px;
  color: var(--muted);
  font-size: 12px;
  font-weight: 850;
  text-align: center;
}

@keyframes carousel-card-in {
  0% {
    filter: saturate(0.72) contrast(0.92);
    opacity: 0;
    transform: translateX(22px) scale(0.972);
  }
  100% {
    filter: saturate(1) contrast(1);
    opacity: 1;
    transform: translateX(0) scale(1);
  }
}

@keyframes carousel-image-in {
  0% {
    filter: blur(10px) brightness(0.75);
    transform: scale(1.075);
  }
  62% {
    filter: blur(0) brightness(1.08);
  }
  100% {
    filter: blur(0) brightness(1);
    transform: scale(1);
  }
}

@keyframes carousel-scan {
  0% {
    opacity: 0;
    transform: translateX(-34%);
  }
  38% {
    opacity: 0.85;
  }
  100% {
    opacity: 0;
    transform: translateX(34%);
  }
}

.video-grid {
  grid-template-columns: 1fr;
  gap: 28px;
}

.video-grid .media-card {
  width: min(100%, 1120px);
  margin-inline: auto;
}

.media-card {
  position: relative;
  margin: 0;
  overflow: hidden;
  border: 1px solid var(--line);
  background:
    linear-gradient(135deg, rgba(248, 246, 236, 0.06), rgba(248, 246, 236, 0.015)),
    #111;
  transition: transform 180ms ease, border-color 180ms ease;
}

.media-card.feature {
  grid-column: span 2;
}

.media-card:hover {
  transform: translateY(-3px);
  border-color: rgba(215, 255, 53, 0.64);
}

.media-card img,
.media-card video {
  width: 100%;
  aspect-ratio: 16 / 9;
  background: #0d0d0c;
  object-fit: contain;
}

.media-card img,
.hero-media img,
.secondary-work img {
  cursor: zoom-in;
}

.media-card figcaption {
  display: flex;
  min-height: 42px;
  align-items: center;
  justify-content: space-between;
  gap: 12px;
  padding: 11px 13px;
  border-top: 1px solid var(--line);
  color: var(--ink);
  font-size: 13px;
  font-weight: 850;
}

.video-card video {
  background: #000;
}

.secondary-section {
  background: rgba(255, 255, 255, 0.025);
}

.secondary-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 16px;
}

.landing-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 24px;
}

.landing-card {
  display: grid;
  gap: 14px;
  border: 1px solid var(--line);
  background: rgba(248, 246, 236, 0.055);
  padding: 16px;
}

.landing-card-heading {
  min-height: auto;
}

.landing-card-heading p {
  margin-bottom: 8px;
  color: var(--cyan);
  font-size: 12px;
  font-weight: 900;
  text-transform: uppercase;
}

.landing-card-heading h3 {
  margin-bottom: 8px;
  font-size: clamp(24px, 3vw, 36px);
  line-height: 1;
}

.landing-card-heading span {
  color: var(--muted);
  font-size: 14px;
}

.landing-photo-carousel,
.landing-video-carousel {
  position: relative;
}

.landing-photo-carousel .media-card,
.landing-video-carousel .media-card {
  margin: 0;
}

.landing-video-card {
  margin: 0;
}

.landing-photo-carousel.carousel-enabled,
.landing-video-carousel.carousel-enabled {
  width: min(100%, 1120px);
  margin-inline: auto;
}

.secondary-work {
  display: grid;
  overflow: hidden;
  border: 1px solid var(--line);
  background: var(--soft);
}

.secondary-work img,
.secondary-work video {
  width: 100%;
  aspect-ratio: 16 / 9;
  background: #111;
  object-fit: contain;
}

.secondary-work div {
  padding: 18px;
}

.secondary-work p {
  margin-bottom: 8px;
  color: var(--cyan);
  font-size: 12px;
  font-weight: 900;
}

.secondary-work h3 {
  margin-bottom: 8px;
  font-size: 22px;
  line-height: 1.1;
}

.secondary-work span {
  color: var(--muted);
  font-size: 14px;
}

.about-contact {
  display: grid;
  max-width: calc(var(--max) + 140px);
  margin-inline: auto;
  grid-template-columns: minmax(0, 1.15fr) minmax(300px, 0.85fr);
  gap: 18px;
}

.about-block,
.contact-block {
  border: 1px solid var(--line);
  background: var(--soft);
  padding: clamp(24px, 5vw, 44px);
}

.contact-block {
  background:
    linear-gradient(145deg, rgba(215, 255, 53, 0.16), rgba(94, 232, 255, 0.08)),
    rgba(248, 246, 236, 0.08);
}

.contact-note {
  margin-top: 16px;
  font-size: 13px;
}

.site-footer {
  display: flex;
  justify-content: space-between;
  gap: 18px;
  padding: 26px clamp(20px, 5vw, 70px);
  border-top: 1px solid var(--line);
  color: var(--muted);
  font-size: 13px;
}

.site-footer a {
  color: var(--acid);
  font-weight: 900;
}

.lightbox {
  position: fixed;
  inset: 0;
  z-index: 100;
  display: grid;
  place-items: center;
  padding: clamp(16px, 4vw, 44px);
  background: rgba(0, 0, 0, 0.9);
  backdrop-filter: blur(18px);
}

.lightbox[hidden] {
  display: none;
}

.lightbox-content {
  display: grid;
  width: min(100%, 1380px);
  max-height: 92vh;
  margin: 0;
  gap: 12px;
}

.lightbox-image {
  width: 100%;
  max-height: calc(92vh - 56px);
  object-fit: contain;
}

.lightbox-caption {
  min-height: 36px;
  color: var(--ink);
  font-size: 14px;
  font-weight: 850;
  text-align: center;
}

.lightbox-close {
  position: fixed;
  top: 18px;
  right: 18px;
  z-index: 120;
  cursor: pointer;
  border: 1px solid var(--line);
  background: rgba(7, 7, 6, 0.82);
  color: var(--ink);
  padding: 11px 14px;
  font-size: 12px;
  font-weight: 950;
}

body.lightbox-open {
  overflow: hidden;
}

.reveal {
  opacity: 0;
  transform: translateY(24px);
  transition: opacity 520ms ease, transform 520ms ease;
}

.reveal.visible {
  opacity: 1;
  transform: translateY(0);
}

@keyframes ticker {
  from {
    transform: translateX(0);
  }
  to {
    transform: translateX(-50%);
  }
}

@keyframes hero-bg-breathe {
  from {
    filter: saturate(0.88) contrast(1.05) brightness(0.86);
    transform: scale(1.018) translate3d(0, 0, 0);
  }
  to {
    filter: saturate(1.04) contrast(1.12) brightness(1);
    transform: scale(1.055) translate3d(-1.3%, -0.8%, 0);
  }
}

@keyframes hero-scan {
  from {
    opacity: 0.24;
    transform: translateX(-9%) rotate(-6deg);
  }
  to {
    opacity: 0.72;
    transform: translateX(9%) rotate(-6deg);
  }
}

@keyframes hero-copy-in {
  from {
    filter: blur(14px);
    opacity: 0;
    transform: translateY(26px);
  }
  to {
    filter: blur(0);
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes title-glow {
  from {
    text-shadow:
      0 1px 0 rgba(255, 255, 255, 0.78),
      0 0 22px rgba(199, 232, 255, 0.18),
      0 28px 90px rgba(0, 0, 0, 0.9);
  }
  to {
    text-shadow:
      0 1px 0 rgba(255, 255, 255, 0.92),
      0 0 44px rgba(199, 232, 255, 0.34),
      0 32px 110px rgba(0, 0, 0, 0.96);
  }
}

@keyframes hero-line-pulse {
  0%,
  100% {
    opacity: 0.36;
    transform: scaleX(0.72);
    transform-origin: left;
  }
  50% {
    opacity: 0.9;
    transform: scaleX(1);
    transform-origin: left;
  }
}

@keyframes hero-ambient-glow {
  from {
    opacity: 0.28;
    transform: translate3d(0, 0, 0) rotate(-7deg) scale(0.94);
  }
  to {
    opacity: 0.68;
    transform: translate3d(-16px, -8px, 0) rotate(-5deg) scale(1.08);
  }
}

@keyframes hero-light-sweep {
  0% {
    opacity: 0;
    transform: translateX(-18%) rotate(-6deg);
  }
  38% {
    opacity: 0.48;
  }
  100% {
    opacity: 0.1;
    transform: translateX(12%) rotate(-6deg);
  }
}

@keyframes hero-float-main {
  0%,
  100% {
    transform: translate3d(0, 0, 0) rotate(-8deg) scale(1);
  }
  50% {
    transform: translate3d(-14px, -10px, 0) rotate(-7deg) scale(1.018);
  }
}

@keyframes hero-float-a {
  0%,
  100% {
    transform: translate3d(0, 0, 0) rotate(6deg);
  }
  50% {
    transform: translate3d(10px, 8px, 0) rotate(7deg);
  }
}

@keyframes hero-float-b {
  0%,
  100% {
    transform: translate3d(0, 0, 0) rotate(-13deg);
  }
  50% {
    transform: translate3d(-10px, -18px, 0) rotate(-10deg);
  }
}

@keyframes hero-float-c {
  0%,
  100% {
    transform: translate3d(0, 0, 0) rotate(13deg);
  }
  50% {
    transform: translate3d(12px, -14px, 0) rotate(16deg);
  }
}

@keyframes hero-orbit {
  from {
    transform: rotate(-22deg);
  }
  to {
    transform: rotate(338deg);
  }
}

@media (max-width: 960px) {
  .site-header {
    position: absolute;
    padding-inline: 16px;
  }

  .nav-links {
    max-width: calc(100vw - 104px);
    overflow-x: auto;
  }

  .hero {
    min-height: auto;
    grid-template-columns: 1fr;
    padding-top: 118px;
    padding-bottom: 48px;
  }

  .hero::before {
    background:
      linear-gradient(180deg, rgba(1, 2, 3, 0.42), rgba(1, 2, 3, 0.12) 44%, rgba(1, 2, 3, 0.78) 100%),
      linear-gradient(90deg, rgba(1, 2, 3, 0.7), rgba(1, 2, 3, 0.08) 62%),
      url("./assets/hero-hi-bg.png");
    background-position: 63% center;
    background-size: cover;
  }

  .hero-stage::after {
    display: none;
  }

  .orbit-one {
    right: -14vw;
    bottom: 30vh;
    width: 76vw;
  }

  .stage-c,
  .orbit-two {
    display: none;
  }

  .hero-copy {
    grid-column: auto;
    max-width: min(100%, 420px);
    padding-top: 16vh;
  }

  h1 {
    font-size: clamp(50px, 12.5vw, 78px);
    line-height: 0.8;
  }

  .work-switcher {
    position: relative;
    top: auto;
  }

  .media-grid,
  .secondary-grid,
  .landing-grid,
  .about-contact {
    grid-template-columns: 1fr;
  }

  .media-card.feature {
    grid-column: span 1;
  }
}

@media (max-width: 560px) {
  .brand-mark {
    min-width: 58px;
    min-height: 38px;
    font-size: 12px;
  }

  .nav-links a {
    min-width: 46px;
    padding-inline: 9px;
    font-size: 12px;
  }

  h1 {
    font-size: clamp(38px, 11.6vw, 50px);
  }

  .panel-copy {
    grid-template-columns: 1fr;
  }

  .hero {
    padding-inline: 16px;
    min-height: 100svh;
  }

  .hero-lead {
    font-size: 14px;
    line-height: 1.75;
  }

  .hero-metrics span {
    font-size: 10px;
  }

  .hero-role {
    font-size: 12px;
    letter-spacing: 0.08em;
  }

  .hero-metrics {
    gap: 6px;
  }

  .hero::before {
    background-position: 64% center;
  }

  .panel-copy p:not(.panel-index),
  .panel-copy .tags {
    grid-column: 1;
  }

  .panel-index {
    font-size: 24px;
  }

  .hero-actions,
  .contact-actions,
  .site-footer {
    flex-direction: column;
  }

  .button {
    width: 100%;
  }
}

@media (prefers-reduced-motion: reduce) {
  *,
  *::before,
  *::after {
    animation-duration: 1ms !important;
    animation-iteration-count: 1 !important;
    scroll-behavior: auto !important;
    transition-duration: 1ms !important;
  }
}

部署说明

这是一个静态网站部署包。上传本文件夹内的全部内容即可上线：
- index.html
- styles.css
- script.js
- resume.pdf
- assets/

部署方式：
1. Vercel / Netlify / Cloudflare Pages：直接上传本文件夹，或把这些文件放到仓库根目录后部署。
2. 普通服务器：把本文件夹内所有内容上传到网站根目录。
3. 对象存储静态站点：上传全部文件，并把默认首页设置为 index.html。

注意：不要只上传 index.html，assets 文件夹必须一起上传，否则图片和视频不会显示。
