<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>荔城镇荔浦市第一小学</title>
    <!-- 外部 CSS -->
    <link rel="stylesheet" href="css/style.css" />
    <!-- Font Awesome 图标库 (用于美化图标) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" />
</head>
<body>

    <!-- ===== 顶部导航栏 ===== -->
    <header class="header" id="header">
        <div class="container header-inner">
            <div class="logo">
                <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Ccircle cx='50' cy='50' r='48' fill='%231565C0'/%3E%3Ctext x='50' y='68' font-size='48' text-anchor='middle' fill='white' font-family='Arial'%3E荔%3C/text%3E%3C/svg%3E" alt="校徽" class="logo-img" />
                <div class="logo-text">
                    <h1>荔城镇荔浦市第一小学</h1>
                    <span>Lichun Town Lipu No.1 Primary School</span>
                </div>
            </div>
            <nav class="nav" id="nav">
                <ul class="nav-list">
                    <li><a href="#home" class="active">首页</a></li>
                    <li><a href="#about">学校概况</a></li>
                    <li><a href="#news">新闻中心</a></li>
                    <li><a href="#gallery">校园风采</a></li>
                    <li><a href="#contact">联系我们</a></li>
                </ul>
                <button class="nav-toggle" id="navToggle" aria-label="切换导航">
                    <span></span><span></span><span></span>
                </button>
            </nav>
        </div>
    </header>

    <!-- ===== 主内容 ===== -->
    <main>

        <!-- ===== 首页横幅 Hero ===== -->
        <section class="hero" id="home">
            <div class="hero-overlay"></div>
            <div class="container hero-content">
                <div class="hero-text">
                    <h2>立德树人 · 知行合一</h2>
                    <p>荔城镇荔浦市第一小学欢迎您！</p>
                    <p class="hero-sub">
                        创办于1956年，历史悠久，底蕴深厚。<br />
                        致力于培养具有民族情怀与世界视野的现代公民。
                    </p>
                    <a href="#about" class="btn btn-primary">了解更多</a>
                </div>
                <div class="hero-image">
                    <!-- 装饰性图形，使用CSS绘制 -->
                    <div class="hero-deco">
                        <div class="deco-circle"></div>
                        <div class="deco-circle"></div>
                        <div class="deco-circle"></div>
                    </div>
                </div>
            </div>
            <!-- 波浪装饰 -->
            <div class="hero-wave">
                <svg viewBox="0 0 1440 120" xmlns="http://www.w3.org/2000/svg">
                    <path d="M0,30 C360,90 720,0 1080,60 C1260,90 1380,60 1440,30 L1440,120 L0,120 Z" fill="#F8F9FA" />
                </svg>
            </div>
        </section>

        <!-- ===== 学校概况 ===== -->
        <section class="section about" id="about">
            <div class="container">
                <div class="section-header">
                    <h2>学校概况</h2>
                    <p>了解我们的历史与使命</p>
                </div>
                <div class="about-grid">
                    <div class="about-text">
                        <h3>荔城镇荔浦市第一小学</h3>
                        <p>
                            荔城镇荔浦市第一小学创建于1956年，是一所具有深厚文化底蕴和优良办学传统的
                            全日制公办小学。学校占地面积约 28000 平方米，现有教学班 36 个，在校学生
                            1600 余人，教职工 120 余人。
                        </p>
                        <p>
                            学校坚持 "立德树人、知行合一" 的办学理念，以 "厚德、博学、笃行、致远"
                            为校训，致力于为学生提供优质的教育资源和全面的发展平台。
                        </p>
                        <div class="about-stats">
                            <div class="stat-item">
                                <span class="stat-number">1956</span>
                                <span class="stat-label">建校年份</span>
                            </div>
                            <div class="stat-item">
                                <span class="stat-number">36</span>
                                <span class="stat-label">教学班</span>
                            </div>
                            <div class="stat-item">
                                <span class="stat-number">1600+</span>
                                <span class="stat-label">在校学生</span>
                            </div>
                            <div class="stat-item">
                                <span class="stat-number">120+</span>
                                <span class="stat-label">教职工</span>
                            </div>
                        </div>
                    </div>
                    <div class="about-image">
                        <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 400 300'%3E%3Crect width='400' height='300' fill='%23E3F2FD'/%3E%3Ctext x='200' y='150' font-size='24' text-anchor='middle' fill='%231565C0' font-family='Arial'%3E🏫 校园全景%3C/text%3E%3C/svg%3E" alt="校园全景" />
                    </div>
                </div>
            </div>
        </section>

        <!-- ===== 新闻中心 ===== -->
        <section class="section news" id="news">
            <div class="container">
                <div class="section-header">
                    <h2>新闻中心</h2>
                    <p>最新校园动态与通知</p>
                </div>
                <div class="news-grid">
                    <article class="news-card">
                        <div class="news-date">
                            <span class="day">28</span>
                            <span class="month">6月</span>
                        </div>
                        <div class="news-content">
                            <h3>2026年秋季学期招生公告</h3>
                            <p>荔城镇荔浦市第一小学2026年秋季学期招生工作即将开始，现将相关事项公告如下……</p>
                            <a href="#" class="news-link">阅读全文 →</a>
                        </div>
                    </article>
                    <article class="news-card">
                        <div class="news-date">
                            <span class="day">20</span>
                            <span class="month">6月</span>
                        </div>
                        <div class="news-content">
                            <h3>校园文化艺术节圆满落幕</h3>
                            <p>6月20日，我校第18届校园文化艺术节在欢声笑语中圆满落幕，同学们展示了精彩的才艺……</p>
                            <a href="#" class="news-link">阅读全文 →</a>
                        </div>
                    </article>
                    <article class="news-card">
                        <div class="news-date">
                            <span class="day">15</span>
                            <span class="month">6月</span>
                        </div>
                        <div class="news-content">
                            <h3>荔浦市小学生运动会我校再创佳绩</h3>
                            <p>在刚刚结束的荔浦市小学生运动会上，我校运动健儿奋勇拼搏，取得了团体总分第二名的好成绩……</p>
                            <a href="#" class="news-link">阅读全文 →</a>
                        </div>
                    </article>
                    <article class="news-card">
                        <div class="news-date">
                            <span class="day">08</span>
                            <span class="month">6月</span>
                        </div>
                        <div class="news-content">
                            <h3>端午节主题教育活动</h3>
                            <p>为弘扬中华优秀传统文化，我校组织开展了"浓情端午·传承文化"主题教育活动……</p>
                            <a href="#" class="news-link">阅读全文 →</a>
                        </div>
                    </article>
                </div>
            </div>
        </section>

        <!-- ===== 校园风采 ===== -->
        <section class="section gallery" id="gallery">
            <div class="container">
                <div class="section-header">
                    <h2>校园风采</h2>
                    <p>记录校园生活的美好瞬间</p>
                </div>
                <div class="gallery-grid">
                    <div class="gallery-item">
                        <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 300 200'%3E%3Crect width='300' height='200' fill='%23BBDEFB'/%3E%3Ctext x='150' y='110' font-size='18' text-anchor='middle' fill='%231565C0' font-family='Arial'%3E📚 书香校园%3C/text%3E%3C/svg%3E" alt="书香校园" />
                        <div class="gallery-overlay">
                            <span>书香校园</span>
                        </div>
                    </div>
                    <div class="gallery-item">
                        <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 300 200'%3E%3Crect width='300' height='200' fill='%23C8E6C9'/%3E%3Ctext x='150' y='110' font-size='18' text-anchor='middle' fill='%232E7D32' font-family='Arial'%3E⚽ 活力操场%3C/text%3E%3C/svg%3E" alt="活力操场" />
                        <div class="gallery-overlay">
                            <span>活力操场</span>
                        </div>
                    </div>
                    <div class="gallery-item">
                        <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 300 200'%3E%3Crect width='300' height='200' fill='%23FFE0B2'/%3E%3Ctext x='150' y='110' font-size='18' text-anchor='middle' fill='%23E65100' font-family='Arial'%3E🎨 艺术课堂%3C/text%3E%3C/svg%3E" alt="艺术课堂" />
                        <div class="gallery-overlay">
                            <span>艺术课堂</span>
                        </div>
                    </div>
                    <div class="gallery-item">
                        <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 300 200'%3E%3Crect width='300' height='200' fill='%23D1C4E9'/%3E%3Ctext x='150' y='110' font-size='18' text-anchor='middle' fill='%234A148C' font-family='Arial'%3E🎵 音乐教室%3C/text%3E%3C/svg%3E" alt="音乐教室" />
                        <div class="gallery-overlay">
                            <span>音乐教室</span>
                        </div>
                    </div>
                    <div class="gallery-item">
                        <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 300 200'%3E%3Crect width='300' height='200' fill='%23B2DFDB'/%3E%3Ctext x='150' y='110' font-size='18' text-anchor='middle' fill='%2300695C' font-family='Arial'%3E🌿 绿色校园%3C/text%3E%3C/svg%3E" alt="绿色校园" />
                        <div class="gallery-overlay">
                            <span>绿色校园</span>
                        </div>
                    </div>
                    <div class="gallery-item">
                        <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 300 200'%3E%3Crect width='300' height='200' fill='%23F8BBD0'/%3E%3Ctext x='150' y='110' font-size='18' text-anchor='middle' fill='%2388004B' font-family='Arial'%3E🏆 荣誉时刻%3C/text%3E%3C/svg%3E" alt="荣誉时刻" />
                        <div class="gallery-overlay">
                            <span>荣誉时刻</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ===== 联系我们 ===== -->
        <section class="section contact" id="contact">
            <div class="container">
                <div class="section-header">
                    <h2>联系我们</h2>
                    <p>欢迎家长与社会各界与我们沟通</p>
                </div>
                <div class="contact-grid">
                    <div class="contact-info">
                        <div class="contact-item">
                            <i class="fas fa-map-marker-alt"></i>
                            <div>
                                <h4>学校地址</h4>
                                <p>广西壮族自治区桂林市荔浦市荔城镇</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <i class="fas fa-phone-alt"></i>
                            <div>
                                <h4>联系电话</h4>
                                <p>0773-1234567</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <i class="fas fa-envelope"></i>
                            <div>
                                <h4>电子邮箱</h4>
                                <p>lpdyxx@edu.lipu.gov.cn</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <i class="fas fa-clock"></i>
                            <div>
                                <h4>办公时间</h4>
                                <p>周一至周五 8:00 - 17:30</p>
                            </div>
                        </div>
                    </div>
                    <div class="contact-form">
                        <h3>在线留言</h3>
                        <form id="contactForm">
                            <div class="form-group">
                                <label for="name">您的姓名</label>
                                <input type="text" id="name" placeholder="请输入姓名" required />
                            </div>
                            <div class="form-group">
                                <label for="email">电子邮箱</label>
                                <input type="email" id="email" placeholder="请输入邮箱" required />
                            </div>
                            <div class="form-group">
                                <label for="message">留言内容</label>
                                <textarea id="message" rows="4" placeholder="请写下您的建议或问题..." required></textarea>
                            </div>
                            <button type="submit" class="btn btn-primary">提交留言</button>
                        </form>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ===== 页脚 ===== -->
    <footer class="footer">
        <div class="container">
            <div class="footer-grid">
                <div class="footer-about">
                    <h3>荔城镇荔浦市第一小学</h3>
                    <p>厚德 · 博学 · 笃行 · 致远</p>
                    <p class="footer-desc">
                        我们致力于为每一位学生提供优质的教育，
                        培养具有民族情怀与世界视野的现代公民。
                    </p>
                </div>
                <div class="footer-links">
                    <h4>快速链接</h4>
                    <ul>
                        <li><a href="#about">学校概况</a></li>
                        <li><a href="#news">新闻中心</a></li>
                        <li><a href="#gallery">校园风采</a></li>
                        <li><a href="#contact">联系我们</a></li>
                    </ul>
                </div>
                <div class="footer-contact">
                    <h4>联系方式</h4>
                    <p><i class="fas fa-map-marker-alt"></i> 荔浦市荔城镇</p>
                    <p><i class="fas fa-phone-alt"></i> 0773-1234567</p>
                    <p><i class="fas fa-envelope"></i> lpdyxx@edu.lipu.gov.cn</p>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2026 荔城镇荔浦市第一小学. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

    <!-- ===== 音乐播放控制按钮 ===== -->
    <button class="music-btn" id="musicBtn" aria-label="播放/暂停背景音乐">
        <i class="fas fa-music"></i>
        <span class="music-status" id="musicStatus">播放</span>
    </button>

    <!-- ===== 回到顶部按钮 ===== -->
    <button class="back-to-top" id="backToTop" aria-label="回到顶部">
        <i class="fas fa-arrow-up"></i>
    </button>

    <!-- ===== 外部 JavaScript ===== -->
    <script src="js/script.js"></script>
</body>
</html>
