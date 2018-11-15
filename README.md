<h1 align="center">
    <br>
    <a href="https://github.com/thedaviddias/Front-End-Performance-Checklist">
        <img src="https://raw.githubusercontent.com/thedaviddias/Front-End-Performance-Checklist/master/images/logo-front-end-performance-checklist.jpg" alt="Front-End Performance Checklist" width="170">
    </a>
    <br>
    <br>
    Front-End Performance Checklist
  <br>
</h1>

<h4 align="center">🎮 
Front-End Performance Checklist này chỉ chạy nhanh hơn những bên khác.
</h4>
<p align="center">Một quy tắc rất đơn giản: "Luôn hướng tới hiệu suất cao cho việc thiết kế và code"</p>

<p align="center">
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome">
  </a>
  <a href="https://discord.gg/btHQRkm">
    <img src="https://img.shields.io/badge/chat-on_discord-4837E2.svg?style=flat-square" alt="Discord">
  </a>
    <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="Licence MIT">
  </a>
</p>

<p align="center">
  <a href="#how-to-use">Hướng dẫn sử dụng</a> • <a href="#contributing">Đóng góp</a> • <a href="http://feedback.frontendchecklist.io/">Lộ trình</a> • <a href="https://www.producthunt.com/posts/front-end-performance-checklist">Tìm những sản phẩm khác</a>
</p>

<p align="center">
  <a href="https://github.com/JohnsenZhou/Front-End-Performance-Checklist">🇨🇳</a>
  <a href="https://github.com/WilliamDASILVA/Front-End-Performance-Checklist">🇫🇷</a>
  <a href="https://github.com/ParkSB/Front-End-Performance-Checklist">🇰🇷</a>  
  <a href="https://github.com/fernandofawkes/Front-End-Performance-Checklist">🇵🇹</a>
  <a href="https://github.com/lex111/Front-End-Performance-Checklist">🇷🇺</a>
</p>

<p align="center">
    <span>Những Checklist khác:</span>
    <br>
  🗂 <a href="https://github.com/thedaviddias/Front-End-Checklist#---------front-end-checklist-">Checklist cho Front-End</a> • 💎 <a href="https://github.com/thedaviddias/Front-End-Design-Checklist#front-end-design-checklist">Checklist về thiết kế Front-End</a>
</p>

## Mục lục

1. **[HTML](#html)**
2. **[CSS](#css)**
3. **[Fonts](#fonts)**
4. **[Images](#images)**
5. **[JavaScript](#javascript)**
6. **[Server](#server) (in progress)**
7. **[JS Frameworks](#performances-and-js-frameworks) (in progress)**

## Giới thiệu

Hiệu suất là một chủ đề rất lớn, nhưng nó không chỉ là chủ đề của "back-end" hay "admin": nó cũng là trách nhiệm của Front-End. Front-End Performance Checklist là một danh sách đầy đủ về các yếu tối mà bạn cần kiểm tra hoặc ít nhất là phải biết đến nó, với tư cách là một lập trình viên Front-Edn và áp dụng vào dự án của bạn (cá nhân hay chuyên nghiệp).


### Sử dụng nó như nào?

Đối với mỗi quy tắc, bạn sẽ có một đoạn giải thích *vì sao* quy tắc này quan trọng và *làm sao* để bạn có thể sửa nó. Để biết thêm thông tin sâu hơn, bạn nên tìm những link dẫn tới công cụ, các bài viết hoặc các tài liệu mà có thể hoàn thiện hơn checklist.

Tất cả những điều trong **Front-End Performance Checklist** là các yếu tố cần thiết để đạt điểm hiệu suất cao hơn nhưng bạn nên tìm những mục có chỉ số ưu tiên hơn để giúp bạn ưu tiên các mục khác. Ở đây có 3 mức ưu tiên:

* ![][low] có nghĩa là mục đó có độ ưu tiên **thấp**.
* ![Medium][medium] có nghĩa là mục đó có độ ưu tiên **trung bình**. Bạn không nên
tránh giải quyết vấn đề ở mục đó.
* ![High][high] có nghĩa là mục đó có độ ưu tiên **cao**. Bạn không thể tránh việc không tuân theo quy tắc đó và  thực hiện các điều chỉnh được đề nghị.

### Các công cụ đánh giá hiệu suất

Đây là danh sách các công cụ bạn có thể sử dụng để kiểm tra hoặc giám sát trang web hay ứng dụng của bạn:

 * 🛠 [WebPagetest: Website kiểm tra hiệu suất và độ tối ưu](https://www.webpagetest.org/)
 * 🛠 ☆ [Dareboost: Website kiểm tra tốc độ và phân tích website](https://www.dareboost.com/) (sử dụng mã WPCDD20 để -20%)
 * 🛠 [Treo: Giám sát tốc độ website](https://treo.sh/?ref=perfchecklist)
 * 🛠 [GTmetrix | Kiểm tra tốc độ website và tối ưu hóa hiệu suất](https://gtmetrix.com/)
 * 🛠 [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
 * 🛠 [Pingdom: Kiểm tra tốc độ của website](https://tools.pingdom.com)
 * 📖 [Giúp cho website nhanh hơn | Google Developers](https://developers.google.com/speed/)
 * 🛠 [Sitespeed.io - Welcome to the wonderful world of Web Performance](https://www.sitespeed.io/)
 * 🛠 [Calibre](https://calibreapp.com/)
 * 🛠 [Website Speed Test | Check Web Performance &raquo; Dotcom-Tools](https://www.dotcom-tools.com/website-speed-test.aspx)
 * 🛠 [Website and Server Uptime Monitoring - Pingdom](https://www.pingdom.com/product/uptime-monitoring/) ([Free Signup Link](https://www.pingdom.com/free))
 * 🛠 [Uptime Robot](https://uptimerobot.com)
 * 🛠 [SpeedCurve: Giám sát hiệu suất của Front-end](https://speedcurve.com)
 * 🛠 [PWMetrics - công cụ CLI và thư viện thu thập các số liệu về hiệu suất](https://github.com/paulirish/pwmetrics)
 * 🛠 [Varvy - Tối ưu tốc độ trang]( https://varvy.com/pagespeed/)
 * 🛠 [Lighthouse - Google]( https://developers.google.com/web/tools/lighthouse/#devtools)
 * 🛠 [Checkbot browser extension - Các phương pháp hay nhất về kiểm thử hiệu suất trang web](https://www.checkbot.io/)
 * 🛠 [Yellow Lab Tools | Kiểm tra để giúp tăng tốc các trang web nặng](https://yellowlab.tools/)

### Tài liệu tham khảo

 * 📹 [The Cost Of JavaScript - YouTube](https://www.youtube.com/watch?v=_bzqF05xsC4) ([text version](https://medium.com/@addyosmani/the-cost-of-javascript-in-2018-7d8950fbb5d4))
 * [AddyOsmani.com - Start Performance Budgeting](https://addyosmani.com/blog/performance-budgets/)
 * 📖 [Get Started With Analyzing Runtime Performance  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/)
 * 📖 [State of the Web | 2018_01_01](https://httparchive.org/reports/state-of-the-web?start=2018_01_01)
 * 📖 [Page Weight Doesn't Matter](https://www.speedshop.co/2015/11/05/page-weight-doesnt-matter.html)
 * 📖 [Front-End Performance Checklist 2018 [PDF, Apple Pages]](https://www.smashingmagazine.com/2018/01/front-end-performance-checklist-2018-pdf-pages/)
 * 📖 [Designing for Performance Weighing Aesthetics and Speed - By Lara Callender Hogan [eBook, Print]](http://designingforperformance.com/index.html)
 * 📖 [Varvy - Web performance glossary](https://varvy.com/performance/)
 * 📖 [fabkrum/web-performance-resources: Up to date collection of valuable web performance resources](https://github.com/fabkrum/web-performance-resources)
 * 📖 [Checkbot - Web Speed Best Practices](https://www.checkbot.io/guide/speed/)
 * 🛠 [Progressive Tooling - A list of community-built, third-party tools that can be used to improve page performance](https://progressivetooling.com/)

---

## HTML

![html]

- [ ] **Tối giản HTML:** ![medium] The HTML code là tối giản, các comment, khoảng trắng và các dòng mới phải loại bỏ khỏi các file trên bản production.

    *Tại sao:*
    > Xóa toàn bộ những khoảng trống, comment, và dòng trống không cần thiết sẽ giảm được kích thước HTML của bạn và tăng tốc thời gian tải trang của bạn và rõ ràng  việc tải xuống cho user của bạn được giảm nhẹ hơn.
    
    *Làm như nào:*
    > Hầu hết các framework đều có plugin tạo điều kiện cho việc tối giản hóa các trang web. Bạn có thể sử dụng một loạt các module NPM mà có thể làm công việc đó cho bạn một cách tự động.

    * 🛠 [HTML minifier | Minify Code](http://minifycode.com/html-minifier/)
    * 🛠 [Online HTML Compressor](http://refresh-sf.com)
    * 📖 [Experimenting with HTML minifier — Perfection Kills](http://perfectionkills.com/experimenting-with-html-minifier/#use_short_doctype)

- [ ] **Loại bỏ những comment không cần thiết:** ![low] Đảm bảo rằng các comment được loại bỏ khỏi trang của bạn.

    *Vì sao:*
    > Các comment không thực sự hữu dụng đối với người dùng và nên được loại bỏ khỏi những file trên production. Một trường hợp mà bạn muốn giữ lại các comments là nếu bạn cần giữ nguyên bản cho một thư viện nào đó.

    *Làm như nào:*
    > ⁃ Hầu hết là các comment có thể bị loại bỏ thông qua việc sử dụng plugin minify HTML.
    
 * 🛠 [remove-html-comments - npm](https://www.npmjs.com/package/remove-html-comments)

- [ ] **Loại bỏ các thuộc tính không cần thiết:** ![low] Các thuộc tính type như `type="text/javascript"` hoặc `type="text/css"` đã không còn bắt buộc nữa và sẽ bị xóa đi.

    ```html
    <!-- Trước khi có HTML5 -->
    <script type="text/javascript">
        // JavaScript code
    </script>

    <!-- Hiện nay -->
    <script>
        // JavaScript code
    </script>
    ```

    *Vì sao:*
    > Type attributes are not necessary as HTML5 implies text/css and text/javascript as defaults. Unused code should be removed when not used by your website or app as they add more weight to your pages.
    > Các thuộc tính type đã không còn cần thiết vì HTML5 đã ngầm hiểu text/css và text/javascript như các giá trị mặc định. Phần code không được sử dụng nên được loại bỏ vì nó làm trang nặng hơn khi không được sử dụng bởi website hoặc ứng dụng của bạn.
     
    *Làm như nào:*
    > ⁃ Chắc chắn là tất cả các thẻ `<link>` và `<script>` của bạn không có bất kì thuộc tính type nào.

    * 📖 [The Script Tag | CSS-Tricks](https://css-tricks.com/the-script-tag/)
   
- [ ] **Luôn luôn đặt các thẻ CSS trước các thẻ Javascript:** ![high] Chắc chắn là phần CSS của bạn luôn được tải trước phần code Javascript.

    ```html
    <!-- Not recommended -->
    <script src="jquery.js"></script>
    <script src="foo.js"></script>
    <link rel="stylesheet" href="foo.css"/>

    <!-- Recommended -->
    <link rel="stylesheet" href="foo.css"/>
    <script src="jquery.js"></script>
    <script src="foo.js"></script>
    ```

    *Vì sao:*
    
    > Việc đặt các thẻ CSS trước bất kì thẻ Javascript nào khiến việc tải xuống song song tốt hơn, giúp tăng tốc render của trình duyệt.
    
    *Làm như nào:*
    
    > Đảm bảo là các thẻ `<link>` và `<style>` trong thẻ `<head>` của bạn luôn luôn đứng trước thẻ `<script>`.
    
    * 📖 [Sắp xếp lại các style và script để tăng tốc trang](https://varvy.com/pagespeed/style-script-order.html)

- [ ] **Giảm thiểu số lượng jframe:** ![high] Use iframes only if you don't have any other technical possibility. Try to avoid iframes as much as you can.
Chỉ sử dụng iframe nếu bạn không có bất cứ một công nghệ khác. Cố gắng tránh việc sử dụng jframe nhiều nhất có thể.

**[⬆ back to top](#table-of-contents)**

## CSS

![css]

- [ ] **Tối giản:** ![high] Tất cả file CSS đều phải tối giản, các comment, khoảng trắng và các dòng mới phải được loại bỏ khỏi các file trong production.

    *Vì sao:*
    > Khi các file CSS được tối giản, nội dung được tải nhanh hơn và tốn ít dữ liệu được gửi về cho client hơn. Điều quan trọng là phải luôn luôn giảm thiểu các file CSS trong bản production. Nó có lợi cho người dùng vì nó áp dụng cho bất kì doanh nghiệp nào muốn giảm thiểu chi phí băng thông và lượng tài nguyên sử dụng.

    *Làm như nào:*
    > ⁃ Sử dụng các công cụ để tối giản các file của ban tự động trước hoặc trong khi xây dựng hay phát triển sản phẩm của bạn.

    * 🛠 [cssnano: Một modular tối giản dựa trên hệ thống PostCSS. - cssnano](https://cssnano.co/)
    * 🛠 [@neutrinojs/style-minify - npm](https://www.npmjs.com/package/@neutrinojs/style-minify)
    * 🛠 [Nén CSS online](http://refresh-sf.com)


- [ ] **Ghép nối:** ![medium] Các file CSS được ghép lại thành file duy nhất *(Không phải lúc nào cũng phù hợp với HTTP/2)*.

    ```html

    <!-- Not recommended -->
    <link rel="stylesheet" href="foo.css"/>
    <link rel="stylesheet" href="bar.css"/>

    <!-- Recommended -->
    <link rel="stylesheet" href="foobar.css"/>
    ```

    *Vì sao:*
    > Nếu bạn còn đang sử dụng HTTP/1, bạn có thể vẫn cần phải ghép nối các files của mình lại, nó không còn đúng thực sự nếu server của bạn sử dụng HTTP/2 (việc kiểm tra lại nên được thực hiện).
    
    *Làm như nào:*
    > ⁃ Use online tool or any plugin before or during your build or your deployment to concatenate your files. <br>
    > ⁃ Sử dụng công cụ online hoặc bất kì một plugin nào đó trước hoặc trong khi xây dựng hoặc phát triển của bạn để ghép nối các file lại với nhau. <br>
    ⁃ Ensure, of course, that concatenation does not break your project.
    ⁃ Đương nhiên là hãy chắc chắn việc ghép nối không phá vỡ project của bạn.

    * 📖 [HTTP: Optimizing Application Delivery - High Performance Browser Networking (O'Reilly)](https://hpbn.co/optimizing-application-delivery/#optimizing-for-http2)
    * 📖 [Performance Best Practices in the HTTP/2 Era](https://deliciousbrains.com/performance-best-practices-http2/)

- [ ] **non-blocking:** ![high] Các file CSS phải không bị khóa để ngăn việc DOM mất nhiều thời gian tải.

    ```html
    <link rel="preload" href="global.min.css" as="style" onload="this.rel='stylesheet'">
    <noscript><link rel="stylesheet" href="global.min.css"></noscript>
    ```

    *Vì sao:*
    > Các file CSS có thể khóa việc tải trang và trì hoãn việc render trang của bạn. Sử dụng `preload` có thể tải các file CSS trước khi trình duyệt bắt đầu hiển thị nội dung của trang.

    *Làm như nào:*
    > ⁃ Bạn cần thêm thuộc tính `rel` với giá trị `preload` và thêm `as="style"` vào thành phần `<link>`.

    * 🛠 [loadCSS của nhóm filament](https://github.com/filamentgroup/loadCSS)
    * 📖 [Ví dụ về việc tải trước CSS sử dụng loadCSS](https://gist.github.com/thedaviddias/c24763b82b9991e53928e66a0bafc9bf)
    * 📖 [Tải trước dữ liệu với rel="preload"](https://developer.mozilla.org/en-US/docs/Web/HTML/Preloading_content)
    * 📖 [Preload: Nó tốt cho cái gì? — Smashing Magazine](https://www.smashingmagazine.com/2016/02/preload-what-is-it-good-for/)

- [ ] **Dộ dài của các class CSS:** ![low]Dộ dài của các class có thể tác động (nhẹ) lên các file HTML và CSS của bạn.

    *Vì sao:*
    > Ngay cả việc tác động lên hiệu suất cũng có thể bị tranh chấp, việc đưa ra quyết định đối với chiến lược đặt tên liên quan tới project của bạn có thể tác động đáng kể tới khả năng bảo trì của bảng các style. Nếu bạn sử dụng BEM, trong một vài trường hợp, bạn có thể kết thúc với các class có nhiều kí tự hơn cần thiết. Việc chọn name và namespace một cách khôn ngoan của bạn luôn là điều quan trọng.

    *Làm như nào:*
    > Việc đặt một giới hạn số lượng các kí tự có thể khiến nhiều người thấy hứng thú nhưng chắc chắn là bạn đã phá vỡ website của bạn trong các component có thể giúp giảm thiểu số lượng class (và các khai báo) với độ dài class của bạn.
    
    * 🛠 [class ngắn và dài · jsPerf](https://jsperf.com/long-vs-short-class)

- [ ] **Unused CSS:** ![medium] Xóa các selector CSS không sử dụng

    *Vì sao:*
    > Loại bỏ các selector CSS không được sử dụng có thể giảm kích thước các file của bạn và tăng tốc độ load nội dung lên.

    *Làm như nào:*
    > ⁃ ⚠️ Hãy luôn luôn kiểm tra nếu framework CSS bạn muốn sử dụng không chứa code chuẩn hóa/reset. Thỉnh thoảng bạn không cần mọi thứ đặt ở trong file reset/chuẩn hóa.
    

    * 🛠 [UnCSS Online](https://uncss-online.com/)
    * 🛠 [PurifyCSS](https://github.com/purifycss/purifycss)
    * 🛠 [PurgeCSS](https://github.com/FullHuman/purgecss)
    * 🛠 [Chrome DevTools Coverage](https://developers.google.com/web/updates/2017/04/devtools-release-notes#coverage)

* [ ] **CSS Critical:** ![high] Phần CSS quan trọng (hoặc "trong màn hình đầu tiên") thu thập tất cả các CSS được sử dụng để render ra phần hiển thị của trang. nó được nhúng trước phần gọi CSS chính của bạn và nằm giữa `<style></style>` trên một dòng duy nhất (tối giản nếu có thể).
    *Vì sao:*
    > Việc đặt CSS quan trọng dạng inline giúp tăng tốc độ render của các trang web, giảm được lượng request tới server.
    *Làm như nào:*
    > Việc tạo các CSS quan trọng bằng các công cụ online hoặc sử dụng plugin như plugin của Addy Asmani đã phát triển.

    * 📖 [Tìm hiểu về Critical CSS](https://www.smashingmagazine.com/2015/08/understanding-critical-css/)
    * 🛠 [Critical của Addy Osmani trên GitHub](https://github.com/addyosmani/critical) automates this.
    * 📖 [Inline các CSS quan trọng để web có hiệu suất tốt hơn | Go Make Things](https://gomakethings.com/inlining-critical-css-for-better-web-performance/)
     * 🛠 [Critical Path CSS Generator - Ưu tiên phần nội dung trong màn hình đầu tiên :: SiteLocity](https://www.sitelocity.com/critical-path-css-generator)
     * 📖 [Giảm kích thước của content trong màn hình đầu tiên
](https://developers.google.com/speed/docs/insights/PrioritizeVisibleContent)

- [ ] **CSS nhúng hay inline:** ![high] Tránh việc sử dụng CSS nhúng hoặc inline trong thẻ `<body>` *(Not valid for HTTP/2)*

    *Vì sao:*
    > Một trong những lý do đầu tiên là vì nó là một cách hay để **phân chia nội dung riêng biệt từ thiết kế**. Nó cũng giúp bạn có khả năng bảo trì code dễ dành hơn và website của bạn luôn truy cập được. Nhưng liên quan tới vấn đề hiệu suất, nó khá đơn giản vì nó giúp giảm kích thước của file và thời gian tải trang HTML.

    *Làm như nào:*
    > Luôn sử dụng stylesheet bên ngoài hoặc nhúng CSS vào thẻ `<head>` của bạn (và phải tuân theo các quy tắc tăng hiệu suất về CSS khác)

    * 📖 [Observe CSS Best Practices: Tránh việc sử dụng CSS Inline](https://www.lifewire.com/avoid-inline-styles-for-css-3466846)

- [ ] **Phân tích các stylesheet phức tạp:** ![high] Việc phân tích stylesheet của bạn có thể giúp bạn tìm thấy lỗi, dư thừa và các selector CSS bị lặp lại.

    *Vì sao:*
    > Thông thường bạn có thể bị dư thừa hoặc lỗi xác thực trong CSS của mình, phân tích các file CSS của bạn và loại bỏ những phần phức tạp này có thể giúp bạn tăng tốc các file CSS (vì trình duyệt của bạn sẽ đọc chúng nhanh hơn)
    
    *Làm như nào:*
    > CSS của bạn cần được tổ chức lại, sử dụng một bộ tiền xử lý CSS có thể giúp bạn. Một vài công cụ online được liệt kê bên dưới cũng giúp bạn phân tích và sửa lỗi code của bạn.

    * 🛠 [TestMyCSS |CSS Tối ưu và kiểm tra hiệu suất ](http://www.testmycss.com/)
    * 🛠 [CSS Stats](https://cssstats.com/)
    * 🛠 [macbre/analyze-css: Selector CSS phức tạp và phân tích hiệu suất](https://github.com/macbre/analyze-css)
    * 🛠 [Project Wallace](https://www.projectwallace.com/) giống như thống kê CSS nhưng lưu trữ dữ liệu thống kê theo thời gian vì vậy bạn có thể theo dõi được các thay đổi của mình

**[⬆ quay lại đầu trang](#table-of-contents)**

## Fonts

![fonts]

* 📖 [Một cuốn sách ngoài lề, Sổ tay Webfont](https://abookapart.com/products/webfont-handbook)

- [ ] **Webfont formats:** ![medium] You are using WOFF2 on your web project or application.

    *Vì sao:*
    > According to Google, the WOFF 2.0 Web Font compression format offers 30% average gain over WOFF 1.0. It's then good to use WOFF 2.0, WOFF 1.0 as a fallback and TTF.

    *Làm như nào:*
    > Check before buying your new font that the provider gives you the WOFF2 format. If you are using a free font, you can always use Font Squirrel to generate all the formats you need.

    * 📖 [WOFF 2.0 – Learn more about the next generation Web Font Format and convert TTF to WOFF2](https://gist.github.com/sergejmueller/cf6b4f2133bcb3e2f64a)
    * 🛠 [Create Your Own @font-face Kits » Font Squirrel](https://www.fontsquirrel.com/tools/webfont-generator)
    * 🛠 [IcoMoon App - Icon Font, SVG, PDF & PNG Generator](https://icomoon.io/app/)
    * 📖 [Using @font-face | CSS-Tricks](https://css-tricks.com/snippets/css/using-font-face/?ref=frontendchecklist)
    * 📖 [Can I use... WOFF2](https://caniuse.com/#feat=woff2)

- [ ] **Use `preconnect` to load your fonts faster:** ![medium]

    ```html
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    ```

    *Vì sao:*
    > When you arrived on a website, your device needs to find out where your site lives and which server it needs to connect with. Your browser had to contact a DNS server and wait for the lookup complete before fetching the resource (fonts, CSS files...). Prefetches and preconnects allow the browser to lookup the DNS information and start establishing a TCP connection to the server hosting the font file. This provides a performance boost because by the time the browser gets around to parsing the css file with the font information and discovering it needs to request a font file from the server, it will already have pre-resolved the DNS information and have an open connection to the server ready in its connection pool.

    *Làm như nào:*
    > ⁃ Before prefetching your webfonts, use webpagetest to evaluate your website <br>
    ⁃ Look for teal colored DNS lookups and note the host that are being requested <br>
    ⁃ Prefetch your webfonts in your `<head>` and add eventually these hostnames that you should prefetch too

    * 📖 [Faster Google Fonts with Preconnect - CDN Planet](https://www.cdnplanet.com/blog/faster-google-webfonts-preconnect/)
    * 📖 [Make Your Site Faster with Preconnect Hints | Viget](https://www.viget.com/articles/make-your-site-faster-with-preconnect-hints/)
    * 📖 [Ultimate Guide to Browser Hints: Preload, Prefetch, and Preconnect - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/guide-to-browser-hints-preload-preconnect-prefetch/)
    * 📖 [A Comprehensive Guide to Font Loading Strategies—zachleat.com](https://www.zachleat.com/web/comprehensive-webfonts/#font-face)
    * 🛠 [typekit/webfontloader: Web Font Loader gives you added control when using linked fonts via @font-face.](https://github.com/typekit/webfontloader)

- [ ] **Webfont size:** ![medium] Webfont sizes don't exceed 300kb (all variants included)

 * 📖 [Font Bytes - Page Weight](https://httparchive.org/reports/page-weight#bytesFont)

- [ ] **Prevent Flash or Invisible Text:** ![medium] Avoid transparent text until the Webfont is loaded

 * 📖 [`font-display` for the Masses](https://css-tricks.com/font-display-masses/)
 * 📖 [CSS font-display: The Future of Font Rendering on the Web](https://www.sitepoint.com/css-font-display-future-font-rendering-web/)

**[⬆ back to top](#table-of-contents)**

## Images

![images]

 * 📖 [Image Bytes in 2018](https://httparchive.org/reports/page-weight#bytesImg)

* [ ] **Images optimization:** ![high] Your images are optimized, compressed without direct impact to the end user.

    *Vì sao:*
    > Optimized images load faster in your browser and consume less data.

    *Làm như nào:*
    > ⁃ Try using CSS3 effects when it's possible (instead of a small image) <br>
    ⁃ When it's possible, use fonts instead of text encoded in your images <br>
    ⁃ Use SVG <br>
    ⁃ Use a tool and specify a level compression under 85.

    * 📖 [Image Optimization | Web Fundamentals | Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization)
    * 📖 [Essential Image Optimization - An eBook by Addy Osmani](https://images.guide/)
    * 🛠 [TinyJPG – Compress JPEG images intelligently](https://tinyjpg.com/)
    * 🛠 [Kraken.io - Online Image Optimizer](https://kraken.io/web-interface)
    * 🛠 [Compressor.io - optimize and compress JPEG photos and PNG images](https://compressor.io/compress)
    * 🛠 [Cloudinary - Image Analysis Tool](https://webspeedtest.cloudinary.com)
    * 🛠 [SVGOMG - Optimize SVG vector graphics files](https://jakearchibald.github.io/svgomg/)


* [ ] **Images format:** ![high] Choose your image format appropriately.

    *Vì sao:*
    > To ensure that your images don't slow your website, choose the format that will correspond to your image. If it's a photo, JPEG is most of the time more appropriate than PNG or GIF. But don't forget to look a the nex-gen formats which can reduce the size of your files. Each image format has pros and cons, it's important to know these to make the best choice possible.

    *Làm như nào:*
    > ⁃ Use [Lighthouse](https://developers.google.com/web/tools/lighthouse/) to identify which images can eventually use **next-gen formats** (like JPEG 2000m JPEG XR or WebP) <br>
    ⁃ Compare different formats, sometimes using PNG8 is better than PNG16, sometimes it's not.

    * 📖 [Serve Images in Next-Gen Formats  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/lighthouse/audits/webp)
    * 📖 [What Is the Right Image Format for Your Website? — SitePoint](https://www.sitepoint.com/what-is-the-right-image-format-for-your-website/)
    * 📖 [PNG8 - The Clear Winner — SitePoint](https://www.sitepoint.com/png8-the-clear-winner/)
    * 📖 [8-bit vs 16-bit - What Color Depth You Should Use And Why It Matters - DIY Photography](https://www.diyphotography.net/8-bit-vs-16-bit-color-depth-use-matters/)

- [ ] **Use vector image vs raster/bitmap:** ![medium] Prefer using vector image rather than bitmap images (when possible).

    *Vì sao:*
    > Vector images (SVG) tend to be smaller than images and SVG's are responsive and scale perfectly. These images can be animated and modified by CSS.

* [ ] **Images dimensions:** ![medium] Set `width` and `height` attributes on `<img>` if the final rendered image size is known.

    *Vì sao:*
    > If height and width are set, the space required for the image is reserved when the page is loaded. However, without these attributes, the browser does not know the size of the image, and cannot reserve the appropriate space to it. The effect will be that the page layout will change during loading (while the images load).

* [ ] **Avoid using Base64 images:** ![medium] You could eventually convert tiny images to base64 but it's actually not the best practice.

    * 📖 [Base64 Encoding & Performance, Part 1 and 2 by Harry Roberts](https://csswizardry.com/2017/02/base64-encoding-and-performance/)
    * 📖 [A closer look at Base64 image performance – The Page Not Found Blog](http://www.andygup.net/a-closer-look-at-base64-image-performance/)
    * 📖 [When to base64 encode images (and when not to) | David Calhoun](https://www.davidbcalhoun.com/2011/when-to-base64-encode-images-and-when-not-to/)
   * 📖 [Base64 encoding images for faster pages | Performance and seo factors](https://varvy.com/pagespeed/base64-images.html)

* [ ] **Lazy loading:** ![medium] Offscreen images are loaded lazily (A noscript fallback is always provided).

    *Vì sao:*
    > It will improve the response time of the current page and then avoid loading unnecessary images that the user may not need.

    *Làm như nào:*
    > ⁃ Use [Lighthouse](https://developers.google.com/web/tools/lighthouse/) to identify how many **images are offscreen**. <br>
    ⁃ Use a JavaScript plugin like the following to lazyload your images. Make sure you target offscreen images only. <br>
    ⁃ Also make sure to lazyload alternative images shown at mouseover or upon other user actions.

    * 🛠 [verlok/lazyload: GitHub](https://github.com/verlok/lazyload)
    * 🛠 [aFarkas/lazysizes: GitHub](https://github.com/aFarkas/lazysizes/)
    * 📖 [Lazy Loading Images and Video  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/lazy-loading-guidance/images-and-video/)
    * 📖 [5 Brilliant Ways to Lazy Load Images For Faster Page Loads - Dynamic Drive Blog](http://blog.dynamicdrive.com/5-brilliant-ways-to-lazy-load-images-for-faster-page-loads/)

* [ ] **Responsive images:** ![medium] Ensure to serve images that are close to your display size.

    *Vì sao:*
    > Small devices don't need images bigger than their viewport. It's recommended to have multiple versions of one image on different sizes.

    *Làm như nào:*
    > ⁃ Create different image sizes for the devices you want to target. <br>
    ⁃ Use `srcset` and `picture` to deliver multiple variants of each image.

     * 📖 [Responsive images - Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

**[⬆ back to top](#table-of-contents)**

## JavaScript

![javascript]

- [ ] **JS Minification:** ![high] All JavaScript files are minified, comments, white spaces and new lines are removed from production files *(still valid if using HTTP/2)*.

    *Vì sao:*
    > Removing all unnecessary spaces, comments and break will reduce the size of your JavaScript files and speed up your site's page load times and obviously lighten the download for your user.

    *Làm như nào:*
    > ⁃ Use the tools suggested below to minify your files automatically before or during your build or your deployment.

    * 🛠 [uglify-js - npm](https://www.npmjs.com/package/uglify-js)
    * 🛠 [Online JavaScript Compressor](http://refresh-sf.com)
    * 📖 [Short read: How is HTTP/2 different? Should we still minify and concatenate?](https://scaleyourcode.com/blog/article/28)

* [ ] **No JavaScript inside:** ![medium] *(Only valid for website)* Avoid having multiple JavaScript codes embedded in the middle of your body. Regroup your JavaScript code inside external files or eventually in the `<head>` or at the end of your page (before `</body>`).

    *Vì sao:*
    > Placing JavaScript embedded code directly in your `<body>` can slow down your page because it loads while the DOM is being built. The best option is to use external files with `async` or `defer` to avoid blocking the DOM. Another option is to place some scripts inside your `<head>`. Most of the time analytics code or small script that need to load before the DOM gets to main processing.

    *Làm như nào:*
    > Ensure that all your files are loaded using `async` or `defer` and decide wisely the code that you will need to inject in your `<head>`.

     * 📖 [11 Tips to Optimize JavaScript and Improve Website Loading Speeds](https://www.upwork.com/hiring/development/11-tips-to-optimize-javascript-and-improve-website-loading-speeds/)

* [ ] **Non-blocking JavaScript:** ![high] JavaScript files are loaded asynchronously using `async` or deferred using `defer` attribute.

    ```html
    <!-- Defer Attribute -->
    <script defer src="foo.js"></script>

    <!-- Async Attribute -->
    <script async src="foo.js"></script>
    ```

    *Vì sao:*
    > JavaScript blocks the normal parsing of the HTML document, so when the parser reaches a `<script>` tag (particularly is inside the `<head>`), it stops to fetch and run it. Adding `async` or `defer` are highly recommended if your scripts are placed in the top of your page but less valuable if just before your `</body>` tag. But it's a good practice to always use these attributes to avoid any performance issue.

    *Làm như nào:*
    > ⁃ Add `async` (if the script don't rely on other scripts) or `defer` (if the script relies upon or relied upon by an async script) as an attribute to your script tag. <br>
    ⁃ If you have small scripts, maybe use inline script place above async scripts.

    * 📖 [Remove Render-Blocking JavaScript](https://developers.google.com/speed/docs/insights/BlockingJS)
    * 📖 [Defer loading JavaScript](https://varvy.com/pagespeed/defer-loading-javascript.html)

* [ ] **Optimized and updated JS libraries:** ![medium] All JavaScript libraries used in your project are necessary (prefer Vanilla JavaScript for simple functionalities), updated to their latest version and don't overwhelm your JavaScript with unnecessary methods.

    *Vì sao:*
    > Most of the time, new versions come with optimization and security fix. You should use the most optimized code to speed up your project and ensure that you'll not slow down your website or app without outdated plugin.

    *Làm như nào:*
    > If your project use NPM packages, [npm-check](https://www.npmjs.com/package/npm-check) is a pretty interesting library to upgrade / update your libraries.
    > [Greenkeeper](https://greenkeeper.io/) can automatically look for your dependencies and suggest an update evey time a new version is out.

    * 📖 [You may not need jQuery](http://youmightnotneedjquery.com/)
    * 📖 [Vanilla JavaScript for building powerful web applications](https://plainjs.com/)

- [ ] **Check dependencies size limit:** ![low] Ensure to use wisely external libraries, most of the time, you can use a lighter library for a same functionality.

    *Vì sao:*
    > You may be tempted to use one of the 745 000 packages you can find on [npm](https://www.npmjs.com/), but you need to choose the best package for your needs. For example, MomentJS is an awesome library but with a lot of methods you may never use, that's why Day.js was created. It's just 2kB vs 16.4kB gz for Moment.

    *Làm như nào:*
    > Always compare and choose the best and lighter library for your needs. You can also use tools like [npm trends](http://www.npmtrends.com/) to compare NPM package downloads counts or [Bundlephobia](https://bundlephobia.com/) to know the size of your dependencies.

    * 🛠 [ai/size-limit: Prevent JS libraries bloat. If you accidentally add a massive dependency, Size Limit will throw an error.](https://github.com/ai/size-limit)
    * 🛠 [webpack-bundle-analyzer - npm](https://www.npmjs.com/package/webpack-bundle-analyzer)
    * 📖 [Size Limit: Make the Web lighter — Martian Chronicles, Evil Martians’ team blog](https://evilmartians.com/chronicles/size-limit-make-the-web-lighter)

- [ ] **JavaScript Profiling:** ![medium] Check for performance problems in your JavaScript files (and CSS too).

    *Vì sao:*
    > JavaScript complexity can slow down runtime performance. Identifying these possible issues are essential to offer the smoothest user experience.

    *Làm như nào:*
    > Use the Timeline tool in the Chrome Developer Tool to evaluate scripts events and found the one that may take too much time.

     * 📖 [Speed Up JavaScript Execution  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/rendering-tools/js-execution)
    * 📖 [JavaScript Profiling With The Chrome Developer Tools — Smashing Magazine](https://www.smashingmagazine.com/2012/06/javascript-profiling-chrome-developer-tools/)
    * 📖 [How to Record Heap Snapshots  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/memory-problems/heap-snapshots)
    * 📖 [Chapter 22 - Profiling the Frontend - Blackfire](https://blackfire.io/docs/book/22-frontend-profiling)
    * 📖 [30 Tips To Improve Javascript Performance](http://www.monitis.com/blog/30-tips-to-improve-javascript-performance/)

- [ ] **Use of Service Workers:** ![medium] You are using Service Workers in your PWA to cache data or execute possible heavy tasks without impacting the user experience of your application.
   
    * 📖 [Service Workers: an Introduction  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/primers/service-workers/)
    * 📖 [Measuring the Real-world Performance Impact of Service Workers  |  Web  |  Google Developers](https://developers.google.com/web/showcase/2016/service-worker-perf)
    * 📖 [What Are Service Workers and How They Help Improve Performance](https://www.keycdn.com/blog/service-workers/)
    * 📹 [How does a service worker work? - YouTube](https://www.youtube.com/watch?v=__xAtWgfzvc)

**[⬆ back to top](#table-of-contents)**

## Server

![server-side]

- [ ] **Your website is using HTTPS:** ![high] 

    *Vì sao:*
    > HTTPS is not only for ecommerce websites, but for all websites that are exchanging data. Data shared by a user or data shared to an external entity. Modern browsers today limit functionalities for sites that are not secure. For example: geolocation, push notifications and service workers don't work if your instance is not using HTTPS. And today is much more easy to setup a project with an SSL certificate than it was before (and for free, thanks to [Let's Encrypt](https://letsencrypt.org/)).

 * 📖 [Why Use HTTPS? | Cloudflare](https://www.cloudflare.com/learning/security/why-use-https/)
 * 📖 [Enabling HTTPS Without Sacrificing Your Web Performance - Moz](https://moz.com/blog/enabling-https-without-sacrificing-web-performance)
 * 📖 [How HTTPS Affects Website Performance](https://wp-rocket.me/blog/https-affects-website-performance/)
 * 📖 [HTTP versus HTTPS versus HTTP2 - The real story | Tune The Web](https://www.tunetheweb.com/blog/http-versus-https-versus-http2/)
 * 📖 [HTTP vs HTTPS — Test them both yourself](https://www.httpvshttps.com/)

- [ ] **Page weight < 1500 KB (ideally < 500 KB):** ![high] Reduce the size of your page + resources as much as you can.

    *Vì sao:*
    > Ideally you should try to target < 500 KB but the state of web shows that the median of Kilobytes is around 1500 KB (even on mobile). Depending on your target users, network connection, devices, it's important to reduce as much as possible your total Kilobytes to have the best user experience possible.

    *Làm như nào:*
    > ⁃ All the rules inside the Front-End Performance Checklist will help you to reduce as much as possible your resources and your code.

    * 📖 [Page Weight](https://httparchive.org/reports/page-weight#bytesTotal)
    * 🛠 [What Does My Site Cost?](https://whatdoesmysitecost.com/)
    * 🛠 [web - Measure full page size in Chrome DevTools - Stack Overflow](https://stackoverflow.com/questions/38239980/measure-full-page-size-in-chrome-devtools)

- [ ] **Page load times < 3 seconds:** ![high] Reduce as much as possible your page load times to quickly deliver your content to your users.

    *Vì sao:*
    > Faster your website or app is, less you have probability of bounce increases, in other terms you have less chances to lose your user or future client. Enough researches on the subject prove that point.

    *Làm như nào:*
    > Use online tools like [Page Speed Insight](https://developers.google.com/speed/pagespeed/insights/) or [WebPageTest](https://www.webpagetest.org/) to analyze what could be slowing you down and use the Front-End Performance Checklist to improve your load times.

    * 🛠 [Compare your mobile site speed](https://www.thinkwithgoogle.com/feature/mobile/)
    * 🛠 [Test Your Mobile Website Speed and Performance - Think With Google](https://testmysite.thinkwithgoogle.com/intl/en-us)
    * 📖 [Average Page Load Times for 2018 - How does yours compare? - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/average-page-load-times-websites-2018/)

- [ ] **Time To First Byte < 1.3 seconds:** ![high] Reduce as much as you can the time your browser waits before receiving data.

    * 📖 [What is Waiting (TTFB) in DevTools, and what to do about it](https://scaleyourcode.com/blog/article/27)
    * 📖 [Monitoring your servers with free tools is easy](https://scaleyourcode.com/blog/article/7)
    * 📖 [Time to First Byte (TTFB)](https://varvy.com/pagespeed/ttfb.html)
    * 🛠 [Global latency testing tool](https://latency.apex.sh)

* [ ] **Cookie size:** ![medium] If you are using cookies, be sure each cookie doesn't exceed 4096 bytes and your domain name doesn't have more than 20 cookies.

    *Vì sao:*
    > Cookies are exchanged in the HTTP headers between web servers and browsers. It's important to keep the size of cookies as low as possible to minimize the impact on the user's response time.

    *Làm như nào:*
    > Eliminate unnecessary cookies.

    * 📖 [Cookie specification: RFC 6265](https://tools.ietf.org/html/rfc6265)
    * 📖 [Cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
    * 🛠 [Browser Cookie Limits](http://browsercookielimits.squawky.net/)
    * 📖 [Website Performance: Cookies Don't Taste So Good - Monitis Blog](http://www.monitis.com/blog/website-performance-cookies-dont-taste-so-good/)
    * 📖 [Google's Web Performance Best Practices #3: Minimize Request Overhead - GlobalDots Blog](https://www.globaldots.com/googles-web-performance-best-practices-3-minimize-request-overhead/)

- [ ] **Minimizing HTTP requests:** ![high] Always ensure that every file requested are essential for your website or application.
 * 📖 [Combine external CSS](https://varvy.com/pagespeed/combine-external-css.html)
 * 📖 [Combine external JavaScript](https://varvy.com/pagespeed/combine-external-javascript.html)

- [ ] **Use a CDN to deliver your assets:** ![medium] Use a CDN to deliver faster your content over the world.

 * 📖 [10 Tips to Optimize CDN Performance - CDN Planet](https://www.cdnplanet.com/blog/10-tips-optimize-cdn-performance/)
 * 📖 [HTTP Caching  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching)

- [ ] **Serve files from the same protocol:** ![high] Avoid having your website serving files coming from source using HTTP on your website which is using HTTPS for example. If your website is using HTTPS, external files should come from the same protocol.

- [ ] **Serve reachable files:** ![high] Avoid requesting unreachable files (404).
 * 📖 [How to avoid bad requests](https://varvy.com/pagespeed/avoid-bad-requests.html)

- [ ] **Set HTTP cache headers properly:** ![high] Set HTTP headers to avoid expensive number of roundtrips between your browser and the server.
 * 📖 [Using cache-control for browser caching](https://varvy.com/pagespeed/cache-control.html)

- [ ] **GZIP / Brotli compression is enabled:** ![high] Use a compression method such as Gzip or Brotli to reduce the size of your JavaScript files. With a smaller sizes file, users will be able to download the asset faster, resulting in improved performance.

 * 🛠 [Check GZIP compression](https://checkgzipcompression.com/)
 * 🛠 [Check Brotli Compression](https://tools.keycdn.com/brotli-test)
 * 📖 [Can I use... Brotli](https://caniuse.com/#feat=brotli)

**[⬆ back to top](#table-of-contents)**

---
## Performances and JS Frameworks

### Angular
 * 📖 [Angular Performance Checklist](https://github.com/mgechev/angular-performance-checklist)

### React

 * 📖 [Optimizing Performance - React](https://reactjs.org/docs/optimizing-performance.html)
 * 📖 [React image manipulation | Cloudinary](https://cloudinary.com/documentation/react_image_manipulation)
 * 📖 [Debugging React performance with React 16 and Chrome Devtools.](https://building.calibreapp.com/debugging-react-performance-with-react-16-and-chrome-devtools-c90698a522ad)

### Vue

## Performances and CMS

### WordPress

* 🛠 [Test Your Website Speed | WordPress Hosting by @WPEngine](https://wpengine.com/speed-tool/)

#### Articles

 * 📖 [19 Tips to Speed Up WordPress Performance (Updated)](https://www.wpbeginner.com/wordpress-performance-speed/)
 * 📖 [Speed Up Your WordPress - How to Save Images Optimized for Web](https://www.wpbeginner.com/beginners-guide/speed-wordpress-save-images-optimized-web/)

#### Plugins recommended

* 🛠 [Caching Plugin for WordPress - Speed up your website with WP Rocket](https://wp-rocket.me/)
* 🛠 [WP-Sweep | WordPress.org](https://wordpress.org/plugins/wp-sweep/)
* 🛠 [Imagify Image Optimizer | WordPress.org](https://wordpress.org/plugins/imagify/)

---

## Translations

The Front-End Performance Checklist wants to also be available in other languages! Don't hesitate to submit your contribution!

* 🇵🇹 Portuguese: [fernandofawkes/Front-End-Performance-Checklist](https://github.com/fernandofawkes/Front-End-Performance-Checklist)
* 🇨🇳 Chinese: [JohnsenZhou/Front-End-Performance-Checklist](https://github.com/JohnsenZhou/Front-End-Performance-Checklist)
* 🇷🇺 Russian: [lex111/Front-End-Performance-Checklist](https://github.com/lex111/Front-End-Performance-Checklist)
* 🇫🇷 French: [WilliamDASILVA/Front-End-Performance-Checklist](https://github.com/WilliamDASILVA/Front-End-Performance-Checklist)
* 🇰🇷 Korean: [ParkSB/Front-End-Performance-Checklist](https://github.com/ParkSB/Front-End-Performance-Checklist)
* 🇪🇸 Spanish: [dagerzuga/Front-End-Performance-Checklist](https://github.com/dagerzuga/Front-End-Performance-Checklist)

## Contributing

**Open an issue or a pull request to suggest changes or additions.**

## Support

If you have any question or suggestion, don't hesitate to use Discord or Twitter:

* [Chat on Discord](https://discord.gg/btHQRkm)
* [Facebook](https://www.facebook.com/frontendchecklist/)
* [Twitter](https://twitter.com/thedaviddias)

## Author

**Build with ❤️ by [David Dias](https://github.com/thedaviddias) at [@influitive](https://influitive.com/) 🇨🇦**

## Contributors

This project exists thanks to all the people who contribute. [[Contribute]](.github/CONTRIBUTING.md).
<a href="https://github.com/thedaviddias/Front-End-Performance-Checklist/graphs/contributors">
    <img src="https://opencollective.com/front-end-checklist/contributors.svg?width=890" />
</a>


## Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/front-end-checklist#backer)]

<a href="https://opencollective.com/front-end-checklist#backers" target="_blank"><img src="https://opencollective.com/front-end-checklist/backers.svg?width=890"></a>


## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/front-end-checklist#sponsor)]

<a href="https://opencollective.com/front-end-checklist/sponsor/0/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/1/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/2/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/3/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/4/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/5/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/6/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/7/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/8/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/9/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/9/avatar.svg"></a>

## License

[MIT](LICENSE)

All icons are provided by [Icons8](https://icons8.com/)

**[⬆ back to top](#table-of-contents)**

[logo]: images/logo-front-end-performance-checklist.jpg
[html]: images/html.png
[css]: images/css.png
[fonts]: images/fonts.png
[images]: images/images.png
[javascript]: images/javascript.png
[server-side]: images/server-side.png

[low]: https://front-end-checklist.now.sh/low.svg
[medium]: https://front-end-checklist.now.sh/medium.svg
[high]: https://front-end-checklist.now.sh/high.svg
