<h1 align="center">
<br>
  <a href="https://github.com/thedaviddias/Front-End-Performance-Checklist"><img src="https://raw.githubusercontent.com/thedaviddias/Front-End-Performance-Checklist/master/images/logo-front-end-performance-checklist.jpg" alt="Front-End Performance Checklist" width="170"></a>
  <br>
    <br>
  Front-End Performance Checklist
  <br>
</h1>

<h4 align="center">🎮 The only Front-End Performance Checklist that runs faster than the others.</h4>
<p align="center">One simple rule: "Design and code with performance in mind"</p>

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
  <a href="#how-to-use">How To Use</a> • <a href="#contributing">Contributing</a> • <a href="http://feedback.frontendchecklist.io/">Roadmap</a> • <a href="https://www.producthunt.com/posts/front-end-performance-checklist">Product Hunt</a>
</p>

<p align="center">
  <a href="https://github.com/JohnsenZhou/Front-End-Performance-Checklist">🇨🇳</a>
  <a href="https://github.com/WilliamDASILVA/Front-End-Performance-Checklist">🇫🇷</a>
  <a href="https://github.com/ParkSB/Front-End-Performance-Checklist">🇰🇷</a>  
  <a href="https://github.com/fernandofawkes/Front-End-Performance-Checklist">🇵🇹</a>
  <a href="https://github.com/lex111/Front-End-Performance-Checklist">🇷🇺</a>
</p>

<p align="center">
    <span>Other Checklists:</span>
    <br>
  🗂 <a href="https://github.com/thedaviddias/Front-End-Checklist#---------front-end-checklist-">Front-End Checklist</a> • 💎 <a href="https://github.com/thedaviddias/Front-End-Design-Checklist#front-end-design-checklist">Front-End Design Checklist</a>
</p>

## Table of Contents

1. **[HTML](#html)**
2. **[CSS](#css)**
3. **[Fonts](#fonts)**
4. **[Images](#images)**
5. **[JavaScript](#javascript)**
6. **[Server](#server) (in progress)**
7. **[JS Frameworks](#performances-and-js-frameworks) (in progress)**

## Giới thiệu

Performance là một chủ để lớn, nhưng nó không phải luôn là một chủ đề của "back-end" hoặc "admin": nó cũng là một trách nhiệm của Front-End. Front-End Performance Checklist là một danh sách đầy đủ các thành phần bạn nên kiểm tra hoặc ít nhất biết được giống như một Front-End developer và áp dụng vào dự án của bạn (cá nhân và chuyên nghiệp).

### Làm thế nào để sử dụng?

Đối với mỗi quy tắc, bạn sẽ có một đoạn giải thích *tại sao* về quy tắc đó là quan trọng và *làm thế nào* bạn có thể sửa nó. Để biết thêm thông tin chi tiết, bạn nên tìm đến các link mà sẽ được chỉ bởi các công cụ 🛠, 📖 các bài viết hoặc 📹 các media để có thể hoàn thành checklist.

Tất cả các mục trong **Front-End Performance Checklist** là những yếu tố cần thiết để để đạt được điểm số về performance cao nhất nhưng bạn sẽ tìm thấy một chỉ số để giúp bạn ưu tiên một số quy tắc khác. Có 3 mức độ ưu tiên: 

* ![Low][low] nghĩa là mục có ưu tiên **thấp**.
* ![Medium][medium] nghĩa là mục có ưu tiên **trung bình**. Bạn không nên tránh giải quyết mục này.
* ![High][high] nghĩa là mục này có ưu tiên **cao** . Bạn không thể tránh theo dõi các quy tắc này và thực hiện các sửa chữa được đề nghị.

### Các công cụ cho performance

Danh sách các công cụ bạn có thể sử dụng để test hoặc hiển thị website của bạn hoặc ứng dụng:

 * 🛠 [WebPagetest - Website Performance and Optimization Test](https://www.webpagetest.org/)
 * 🛠 ☆ [Dareboost: Website Speed Test and Website Analysis](https://www.dareboost.com/) (use the coupon WPCDD20 for -20%)
 * 🛠 [Treo: Page Speed Monitoring](https://treo.sh/?ref=perfchecklist)
 * 🛠 [GTmetrix | Website Speed and Performance Optimization](https://gtmetrix.com/)
 * 🛠 [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
 * 🛠 [Pingdom Website Speed Test](https://tools.pingdom.com)
 * 📖 [Make the Web Faster | Google Developers](https://developers.google.com/speed/)
 * 🛠 [Sitespeed.io - Welcome to the wonderful world of Web Performance](https://www.sitespeed.io/)
 * 🛠 [Calibre](https://calibreapp.com/)
 * 🛠 [Website Speed Test | Check Web Performance &raquo; Dotcom-Tools](https://www.dotcom-tools.com/website-speed-test.aspx)
 * 🛠 [Website and Server Uptime Monitoring - Pingdom](https://www.pingdom.com/product/uptime-monitoring/) ([Free Signup Link](https://www.pingdom.com/free))
 * 🛠 [Uptime Robot](https://uptimerobot.com)
 * 🛠 [SpeedCurve: Monitor front-end performance](https://speedcurve.com)
 * 🛠 [PWMetrics - CLI tool and lib to gather performance metrics](https://github.com/paulirish/pwmetrics)
 * 🛠 [Varvy - Page speed optimization]( https://varvy.com/pagespeed/)
 * 🛠 [Lighthouse - Google]( https://developers.google.com/web/tools/lighthouse/#devtools)
 * 🛠 [Checkbot browser extension - Checks for web performance best practices](https://www.checkbot.io/)
 * 🛠 [Yellow Lab Tools | Online test to help speeding up heavy web pages](https://yellowlab.tools/)

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

- [ ] **Minified HTML:** ![medium] HTML code được minify, các comment, các khoảng trắng và các dòng mới được loại bỏ khỏi các file production.

    *Tại sao:*
    > Loại bỏ tất cả các khoảng trắng, các comment và xuống dòng không cần thiết sẽ giảm kích thước HTML của bạn và tăng tốc độ thời gian load trang của bạn và chắc chắn làm giảm bớt việc tải xuống cho người dùng của bạn.

    *Cách làm:*
    > Hầu hết các framework đều có các plugin để tối giản hoá các trang web. Bạn có thể sử dụng một loạt các module của NPM để có thể thực hiện job đó một các tự động.

    * 🛠 [HTML minifier | Minify Code](http://minifycode.com/html-minifier/)
    * 🛠 [Online HTML Compressor](http://refresh-sf.com)
    * 📖 [Experimenting with HTML minifier — Perfection Kills](http://perfectionkills.com/experimenting-with-html-minifier/#use_short_doctype)

- [ ] **Loại bỏ các comment không cần thiết:** ![low] Đảm bảo rằng các comment được loại bỏ khỏi các trang của bạn.

    *Tại sao:*
    > Các comment không thực sự hữu ích cho người dùng và nên được loại bỏ khỏi các file production. Trong trường hợp bạn muốn giữ các comment nếu bạn cần giữ lại bản gốc của một thư viện.

    *Cách làm:*
    > ⁃ Hầu hết mọi lần, các comment có thể được loại bỏ khi sử dụng một plugin cho HTML minify.

 * 🛠 [remove-html-comments - npm](https://www.npmjs.com/package/remove-html-comments)

- [ ] **Loại bỏ các thuộc tính không cần thiết:** ![low] Các thuộc tính type giống như là `type="text/javascript"` hoặc `type="text/css"` không còn yêu cầu bắt buộc nữa và nên được bỏ đi.

    ```html
    <!-- Before HTML5 -->
    <script type="text/javascript">
        // JavaScript code
    </script>

    <!-- Today -->
    <script>
        // JavaScript code
    </script>
    ```

    *Tại sao:*
    > Thuộc tính type là không cần thiết trong HTML 5 ngầm hiểu text/css và text/javascript là mặc định. Code không sử dụng nên được loại bỏ khi không được sử dụng bởi website hoặc ứng dụng của bạn, chúng thêm vào làm nặng các trang của bạn.

    *Cách làm:*
    > ⁃ Đảm bảo rằng tất cả các thẻ `<link>` and `<script>` của bạn không chứa bất kỳ thuộc tính type nào.

    * 📖 [The Script Tag | CSS-Tricks](https://css-tricks.com/the-script-tag/)
   
- [ ] **Luôn luôn đặt các thẻ CSS trước các thẻ JavaScript:** ![high] Đảm bảo rằng CSS của bạn luôn luôn được load trước khi có code Javascript.

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

    *Tại sao:*
    > Có các thẻ CSS trước bất kỳ thẻ Javascript nào sẽ tốt hơn, tải xuống song song giúp tăng tốc độ về thời gian hiển thị của trình duyệt.

    *Cách làm:*
    > ⁃ Đảm bảo rằng `<link>`  và `<style>` trong `<head>` là luôn luôn ở trước `<script>`.

    * 📖 [Ordering your styles and scripts for pagespeed](https://varvy.com/pagespeed/style-script-order.html)

- [ ] **Giảm thiểu số lượng iframe:** ![high] Chỉ sử dụng iframe nếu bạn không có khả năng sử dụng kỹ thuật khác. Cố gắng tránh các iframe nhiều nhất có thể.

**[⬆ back to top](#table-of-contents)**

## CSS

![css]

- [ ] **Minification:** ![high] Tất cả các file CSS được minify, các comment, các khoảng trắng và các dòng trống được loại bỏ ra các file production.

    *Tại sao:*
    > Khi các file CSS được minify, nội dung được load nhanh hơn và ít dữ liệu hơn được gửi đến client. Điều quan trọng là luôn luôn minify các file CSS trong production. Nó có lợi cho người dùng vì nó làm cho bất kỳ business người muốn giảm chi phi băng thông và giảm tài nguyên sử dụng.

    *Cách làm:*
    > ⁃ Sử dụng các công cụ để minify các file của bạn tự động trước khi hoặc trong khi build hoặc trong khi deploymennt.

    * 🛠 [cssnano: A modular minifier based on the PostCSS ecosystem. - cssnano](https://cssnano.co/)
    * 🛠 [@neutrinojs/style-minify - npm](https://www.npmjs.com/package/@neutrinojs/style-minify)
    * 🛠 [Online CSS Compressor](http://refresh-sf.com)


- [ ] **Ghép nối:** ![medium] Các file CSS được nối lại thành một file riêng *(Không phải lúc nào cũng đúng với HTTP/2)*.

    ```html

    <!-- Not recommended -->
    <link rel="stylesheet" href="foo.css"/>
    <link rel="stylesheet" href="bar.css"/>

    <!-- Recommended -->
    <link rel="stylesheet" href="foobar.css"/>
    ```

    *Tại sao:*
    > Nếu bạn vẫn sử dụng HTTP/1, bạn có thể vẫn cần nối các file, nó ít đúng nếu server của bạn sử dụng HTTP/2 (Các test nên được thực hiện).

    *Cách làm:*
    > ⁃ Sử dụng công cụ online hoặc bất kỳ plugin nào trước khi hoặc trong khi build hoặc deployment các file nối của bạn. <br>
    ⁃ Tất nhiên, đảm bảo các file nối không làm vỡ project của bạn.

    * 📖 [HTTP: Optimizing Application Delivery - High Performance Browser Networking (O'Reilly)](https://hpbn.co/optimizing-application-delivery/#optimizing-for-http2)
    * 📖 [Performance Best Practices in the HTTP/2 Era](https://deliciousbrains.com/performance-best-practices-http2/)

- [ ] **Non-blocking:** ![high] Các file CSS cần ở trạng thái non-blocking để ngăn DOM mất thời gian load.

    ```html
    <link rel="preload" href="global.min.css" as="style" onload="this.rel='stylesheet'">
    <noscript><link rel="stylesheet" href="global.min.css"></noscript>
    ```

    *Tại sao:*
    > Các file CSS files có thể block trang web load và delay quá trình render của trang. Sử dụng `preload` có thể thực sự load các file CSS trước khi browser bắt đầu hiển thị nội dung của trang.

    *Cách làm:*
    > ⁃ Bạn cần thêm thuộc tính `rel` với giá trị `preload` value và thêm `as="style"` trên `<link>` element.

    * 🛠 [loadCSS by filament group](https://github.com/filamentgroup/loadCSS)
    * 📖 [Example of preload CSS using loadCSS](https://gist.github.com/thedaviddias/c24763b82b9991e53928e66a0bafc9bf)
    * 📖 [Preloading content with rel="preload"](https://developer.mozilla.org/en-US/docs/Web/HTML/Preloading_content)
    * 📖 [Preload: What Is It Good For? — Smashing Magazine](https://www.smashingmagazine.com/2016/02/preload-what-is-it-good-for/)

- [ ] **Độ dài của các class CSS:** ![low] Độ dài của các class của bạn có thể có một ảnh hưởng (nhẹ) lên các file HTML và CSS của bạn.

    *Tại sao:*
    > Ngay cả việc tác động lên hiệu suất cũng có thể bị tranh chấp, việc đưa ra quyết định đối với chiến lược đặt tên liên quan tới project của bạn có thể tác động đáng kể tới khả năng bảo trì của bảng các style.  Nếu bạn đang sử dụng BEM, trong một vài class bạn có thể kết thúc với các class có nhiều ký tự hơn cần thiết. Việc chọn tên và namespace không ngoan luôn là điều quan trọng.

    *Cách làm:*
    > Đặt một giới hạn về số lượng ký tự có thể hấp dẫn cho một số người, nhưng đảm bảo rằng bạn không làm vỡ website của bạn trong các thành phần có thể giúp làm giảm số lượng các class (và các khai báo) và kích thước của các class.

    * 🛠 [long vs short class · jsPerf](https://jsperf.com/long-vs-short-class)

- [ ] **CSS không sử dụng:** ![medium] Loại bỏ các selector CSS không sử dụng.

    *Tại sao:*
    > Việc loại bỏ các CSS selector không sử dụng có thể làm giảm kích thước các file của bạn và tăng tốc độg load các tài nguyên của bạn.

    *Cách làm:*
    > ⁃ ⚠️ Luôn luôn kiểm tra nếu các framework CSS mà bạn muốn sử dụng không sẵn sàng có code để reset / normalize được include. Thỉnh thoảng bạn có thể không cần mọi thú nằm trong file reset / normalize.

    * 🛠 [UnCSS Online](https://uncss-online.com/)
    * 🛠 [PurifyCSS](https://github.com/purifycss/purifycss)
    * 🛠 [PurgeCSS](https://github.com/FullHuman/purgecss)
    * 🛠 [Chrome DevTools Coverage](https://developers.google.com/web/updates/2017/04/devtools-release-notes#coverage)

* [ ] **CSS Critical:** ![high] CSS critical (hoặc "trong màn hình đầu tiên") tập hợp tất cả CSS được sử dụng để render phần hiển thị của trang. Nó được nhúng trước lời gọi principal CSS và giữa `<style></style>` trong một dòng riêng(được minify nếu khả thi).

    *Tại sao:*
    > Inlining critical CSS giúp tăng tốc độ render của các trang web giảm số lượng các request đến server.

    *Cách làm:*
    > Tạo CSS critical với các công cụ online hoặc sử dụng một plugin giống như Osmani đã phát triển.

    * 📖 [Understanding Critical CSS](https://www.smashingmagazine.com/2015/08/understanding-critical-css/)
    * 🛠 [Critical by Addy Osmani on GitHub](https://github.com/addyosmani/critical) automates this.
    * 📖 [Inlining critical CSS for better web performance | Go Make Things](https://gomakethings.com/inlining-critical-css-for-better-web-performance/)
     * 🛠 [Critical Path CSS Generator - Prioritize above the fold content :: SiteLocity](https://www.sitelocity.com/critical-path-css-generator)
     * 📖 [Reduce the size of the above-the-fold content
](https://developers.google.com/speed/docs/insights/PrioritizeVisibleContent)

- [ ] **CSS nhúng hoặc inline:** ![high] Tránh sử dụng CSS nhúng hoặc inline phía trong `<body>` *(Không hợp lệ cho HTTP/2)*

    *Tại sao:*
    > Một trong những lý do đầu tiên bởi vì nó các làm tốt để **tách nội dung ra khỏi design**. Nó cũng giúp bạn có code dễ bảo trì hơn và giữ truy cập của site. Nhưng về hiệu năng, nó đơn giản chỉ vì nó làm giảm kích thước file của các trang HTM và giảm thời gian load.

    *Cách làm:*
    > Luôn luôn sử dụng CSS stylesheet ngoài hoặc nhúng trong thẻ `<head>` (và thực hiện theo các quy tắc khác về hiệu năng CSS)

    * 📖 [Observe CSS Best Practices: Avoid CSS Inline Styles](https://www.lifewire.com/avoid-inline-styles-for-css-3466846)

- [ ] **Phân tích các stylesheet phức tạp:** ![high] Phân tích các stylesheet của bạn có thể giúp bạn gắn cờ cho các vấn đề, các selector CSS dư thừa và trùng lặp.

    *Tại sao:*
    > Đôi khi bạn có thể có các lỗi dư thừa  hoặc validation trong CSS của bạn phân tích các file CSS và loại bỏ những phức tạp này có thể giúp bạn tăng tốc độ các file CSS (bởi vì trình duyệt của bạn sẽ đọc chúng nhanh hơn)

    *Cách làm:*
    > CSS của bạn nên được tổ chức lại, sử dụng một bộ tiền xử lý CSS có thể giúp bạn điều đó. Một vài công cụ online được liệt kê ở dưới có thể giúp bạn phân tích sự chính xác code của bạn.

    * 🛠 [TestMyCSS | Optimize and Check CSS Performance](http://www.testmycss.com/)
    * 🛠 [CSS Stats](https://cssstats.com/)
    * 🛠 [macbre/analyze-css: CSS selectors complexity and performance analyzer](https://github.com/macbre/analyze-css)
    * 🛠 [Project Wallace](https://www.projectwallace.com/) giống như thống kê CSS nhưng lưu trữ dữ liệu thống kê theo thời gian vì vậy bạn có thể theo dõi được các thay đổi của mình


**[⬆ back to top](#table-of-contents)**

## Fonts

![fonts]

* 📖 [A Book Apart, Webfont Handbook](https://abookapart.com/products/webfont-handbook)

- [ ] **Webfont formats:** ![medium] Bạn đang sử dụng  WOFF2 trên dự án web hoặc ứng dụng của bạn.

    *Tại sao:*
    > Theo Google, định dạng nén WOFF 2.0 Web Font manng lại hiệu quả trung bình 30% so với WOFF 1.0. Điều đó là tốt để sử dụng WOFF 2.0, WOFF 1.0 như một TTF dự phòng.

    *Cách làm:*
    > Kiểm tra trước khi mua bộ font mới xem nhà cung cấp có đưa bạn định dạng WOFF2 không. Nếu bạn đang sử dụng font miễn phí, bạn có thể luôn luôn sử dụng Font Squirrel để tạo ra tất cả các định dạng bạn cần.

    * 📖 [WOFF 2.0 – Learn more about the next generation Web Font Format and convert TTF to WOFF2](https://gist.github.com/sergejmueller/cf6b4f2133bcb3e2f64a)
    * 🛠 [Create Your Own @font-face Kits » Font Squirrel](https://www.fontsquirrel.com/tools/webfont-generator)
    * 🛠 [IcoMoon App - Icon Font, SVG, PDF & PNG Generator](https://icomoon.io/app/)
    * 📖 [Using @font-face | CSS-Tricks](https://css-tricks.com/snippets/css/using-font-face/?ref=frontendchecklist)
    * 📖 [Can I use... WOFF2](https://caniuse.com/#feat=woff2)

- [ ] **Sử dụng `preconnect` để load các font của bạn nhanh hơn:** ![medium]

    ```html
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    ```

    *Tại sao:*
    > Khi bạn đi đến một website, thiết bị của bạn cần tìm xem nơi mà site của bạn chạy và server cần để kết nối đến. Trình duyệt của bạn phải liên hệ đến DNS server và chờ cho đến khi việc lookup hoàn thành trước khi lấy tài nguyên (fonts, CSS files...). Fetch trước và kết nối trước cho phép trình duyệt lookup các thông tin và bắt đầu khởi tạo một kết nối TCP đến server file font. Điều đó cung cấp hiệu năng khởi động bời vì vào thời điểm trình duyệt phân tích cú pháp file css với thông tin font và phát hiện ra nó cần phải request một file font từ server, nó sẽ đã được giải quyết trước thông tin DNS và có một kết nối mở với server đã sẵn sàng trong kết nối của nó.

    *Cách làm:*
    > ⁃ Trước khi prefetch các webfont, sử dụng webpagetest để đánh giá website của bạn <br>
    ⁃ Tìm teal colored DNS lookups và lưu ý host đang được request <br>
    ⁃ Prefetch các webfont của bạn trong `<head>` và thêm cuối cùng các tên host mà bạn cũng nên prefetch

    * 📖 [Faster Google Fonts with Preconnect - CDN Planet](https://www.cdnplanet.com/blog/faster-google-webfonts-preconnect/)
    * 📖 [Make Your Site Faster with Preconnect Hints | Viget](https://www.viget.com/articles/make-your-site-faster-with-preconnect-hints/)
    * 📖 [Ultimate Guide to Browser Hints: Preload, Prefetch, and Preconnect - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/guide-to-browser-hints-preload-preconnect-prefetch/)
    * 📖 [A Comprehensive Guide to Font Loading Strategies—zachleat.com](https://www.zachleat.com/web/comprehensive-webfonts/#font-face)
    * 🛠 [typekit/webfontloader: Web Font Loader gives you added control when using linked fonts via @font-face.](https://github.com/typekit/webfontloader)

- [ ] **Webfont size:** ![medium] Kích thước Webfont không vượt quá 300kb (bao gồm tất cả các biến thể)

 * 📖 [Font Bytes - Page Weight](https://httparchive.org/reports/page-weight#bytesFont)

- [ ] **Prevent Flash hoặc Invisible Text:** ![medium] Tránh text trong suốt cho đến khi  Webfont được load

 * 📖 [`font-display` for the Masses](https://css-tricks.com/font-display-masses/)
 * 📖 [CSS font-display: The Future of Font Rendering on the Web](https://www.sitepoint.com/css-font-display-future-font-rendering-web/)

**[⬆ back to top](#table-of-contents)**

## Các ảnh

![images]

 * 📖 [Image Bytes in 2018](https://httparchive.org/reports/page-weight#bytesImg)

* [ ] **Tối ưu ảnh:** ![high] Các ảnh của bạn được tối ưu, được nén mà không ảnh hưởng trực tiếp đến người dùng cuối.

    *Tại sao:*
    > Các ảnh được tối ưu load nhanh hơn trên trình duyệt của bạn và sử dụng ít dữ liệu hơn.

    *Cách làm:*
    > ⁃ Thử sử dụng các CSS3 effect khi nó khả thị (thay vì một ảnh nhỏ) <br>
    ⁃ Khi nó khả thi, sử dụng các font để thay thế các text encode trong ảnh của bạn<br>
    ⁃ Sử dụng SVG <br>
    ⁃ Sử dụng một công cụ và chỉ định một mức độ nén dưới 85.

    * 📖 [Image Optimization | Web Fundamentals | Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization)
    * 📖 [Essential Image Optimization - An eBook by Addy Osmani](https://images.guide/)
    * 🛠 [TinyJPG – Compress JPEG images intelligently](https://tinyjpg.com/)
    * 🛠 [Kraken.io - Online Image Optimizer](https://kraken.io/web-interface)
    * 🛠 [Compressor.io - optimize and compress JPEG photos and PNG images](https://compressor.io/compress)
    * 🛠 [Cloudinary - Image Analysis Tool](https://webspeedtest.cloudinary.com)
    * 🛠 [SVGOMG - Optimize SVG vector graphics files](https://jakearchibald.github.io/svgomg/)


* [ ] **Định dạng ảnh:** ![high] Chọn Choose định dạng ảnh thích hợp.

    *Tại sao:*
    > Để đảm bảo ảnh của bạn không làm chậm website của bạn, chọn định dạng sẽ được trao đổi đến ảnh của bạn.Nếu nó là một ảnh, JPEG thì hầu hết phù hợp thời gian hơn PNG hoặc GIF. Nhưng đừng quên tìm kiếm định dạng nex-gen mà có thể giảm kích thước các file của bạn. Mỗi định dạng ảnh có ưu và nhược điểm, việc biết điều này là quan trọng để đưa ra sự lựa chọn phù hợp.

    *Cách làm:*
    > ⁃ Sử dụng [Lighthouse](https://developers.google.com/web/tools/lighthouse/) để xác định ảnh nào cuối cùng được sử dụng **định dạng next-gen** (giống như JPEG 2000m JPEG XR hoặc WebP) <br>
    ⁃ So sánh các định dạng khác nhau, đôi khi sử dụng PNG8 tốt hơn PNG16, đôi khi lại không.

    * 📖 [Serve Images in Next-Gen Formats  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/lighthouse/audits/webp)
    * 📖 [What Is the Right Image Format for Your Website? — SitePoint](https://www.sitepoint.com/what-is-the-right-image-format-for-your-website/)
    * 📖 [PNG8 - The Clear Winner — SitePoint](https://www.sitepoint.com/png8-the-clear-winner/)
    * 📖 [8-bit vs 16-bit - What Color Depth You Should Use And Why It Matters - DIY Photography](https://www.diyphotography.net/8-bit-vs-16-bit-color-depth-use-matters/)

- [ ] **Sử dụng ảnh vector với raster/bitmap:** ![medium] Sử dụng ảnh vector hơn ảnh bitmap (khi khả thi).

    *Tại sao:*
    > Các ảnh vector (SVG) có xu hướng bé hơn các ảnh khác và SVG thì có khả năng responsive và hoàn toàn mở rộng. Những ảnh này có thể là ảnh hoạt hình và được chỉnh sửa bởi CSS.

* [ ] **Kích thước ảnh:** ![medium] Thiết lập các thuộc tính `width` và  `height` trên thẻ `<img>` nếu kích thước ảnh được render ra là biết.

    *Tại sao:*
    > Nếu chiều cao và chiều rộng được thiết lập, không gian cần thiết cho  hình ảnh được khoảng trắng được yêu cầu được dành riêng khi page được load. Tuy nhiên, không có các thuộc tính này, trình duyệt không biết kích thước của ảnh và có thể không để dành khoảng không gian cho nó.Hiệu ứng về layout trang sẽ thay đổi trong khi load (trong khi ảnh load).

* [ ] **Tránh sử dụng ảnh Base64:** ![medium] Bạn có thể convert các ảnh nhỏ sang dạng base4 nhưng đó không phải là cách làm tốt nhất.

    * 📖 [Base64 Encoding & Performance, Part 1 and 2 by Harry Roberts](https://csswizardry.com/2017/02/base64-encoding-and-performance/)
    * 📖 [A closer look at Base64 image performance – The Page Not Found Blog](http://www.andygup.net/a-closer-look-at-base64-image-performance/)
    * 📖 [When to base64 encode images (and when not to) | David Calhoun](https://www.davidbcalhoun.com/2011/when-to-base64-encode-images-and-when-not-to/)
   * 📖 [Base64 encoding images for faster pages | Performance and seo factors](https://varvy.com/pagespeed/base64-images.html)

* [ ] **Lazy loading:** ![medium] Hình ảnh trên màn hình được load theo kiểu lazily (Một noscript fallback luôn luôn được cung cấp).

    *Tại sao:*
    > Nó sẽ cải thiện thời gian phản hồi của trang hiện tại và sau đó tránh việc load các hình ảnh không cần thiết mà người dùng có thể không cần.

    *Cách làm:*
    > ⁃ Sử dụng [Lighthouse](https://developers.google.com/web/tools/lighthouse/) để xác định có bao nhiêu **ảnh là dạng offscreen**. <br>
    ⁃ Sử dụng một JavaScript plugin để lazyload các ảnh của bạn. Đảm bảo mục tiêu chỉ có các ảnh offscreen. <br>
    ⁃ Cũng đảm bảm rằng để  lazyload các ảnh thay thế hiển thị  khi di chuyển chuột qua hoặc người dùng khác thực hiện hành động.

    * 🛠 [verlok/lazyload: GitHub](https://github.com/verlok/lazyload)
    * 🛠 [aFarkas/lazysizes: GitHub](https://github.com/aFarkas/lazysizes/)
    * 📖 [Lazy Loading Images and Video  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/lazy-loading-guidance/images-and-video/)
    * 📖 [5 Brilliant Ways to Lazy Load Images For Faster Page Loads - Dynamic Drive Blog](http://blog.dynamicdrive.com/5-brilliant-ways-to-lazy-load-images-for-faster-page-loads/)

* [ ] **Responsive các ảnh:** ![medium] Đảm bảo để đưa ra các ảnh gần với kích thước hiển thị của bạn.

    *Tại sao:*
    > Các thiết bị nhỏ không cần các ảnh lớn hơn khung hình của chúng. Bạn nên có nhiều phiên bản của một ảnh trên các kích thước khác nhau.

    *Cách làm:*
    > ⁃ Tạo các kích thước ảnh khác nhau cho thiết bị bạn muốn nhắm tới.<br>
    ⁃ Sử dụng `srcset` và `picture` để phân phối nhiều biến thể của hình ảnh.

     * 📖 [Responsive images - Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

**[⬆ back to top](#table-of-contents)**

## JavaScript

![javascript]

- [ ] **JS Minification:** ![high] Tất cả các file JavaScript được minify, các comment, khoảng trắng và các dòng mứoi được xoá khỏi các file production *(Vẫn hợp lệ nếu sử dụng HTTP/2)*.

    *Tại sao:*
    > Loại bỏ tất cả các khoảng trắng, comment và xuống dòng không cần thiết sẽ giảm kích thước các file JavaScript và tăng tốc độ load trang của site và rõ ràng làm nhẹ quá trình tải xuống của người dùng.

    *Cách làm:*
    > ⁃ Sử dụng các công cụ được gợi ý dưới đây để minify các file tự động trước hoặc trong khi build hoặc deployment của bạn.

    * 🛠 [uglify-js - npm](https://www.npmjs.com/package/uglify-js)
    * 🛠 [Online JavaScript Compressor](http://refresh-sf.com)
    * 📖 [Short read: How is HTTP/2 different? Should we still minify and concatenate?](https://scaleyourcode.com/blog/article/28)

* [ ] **Không để JavaScript bên trong:** ![medium] *(chỉ đúng cho website)* Tránh có nhiều code JavaScript được nhúng vào giữa body của bạn. Tập hợp lại các code Javascript vào trong các file ngoài hoặc cuối thẻ  `<head>` hoặc cuối trang (trước `</body>`).

    *Tại sao:*
    > Đặt các code nhúng JavaScript trực tiếp trong `<body>` có thể làm chậm việc tải xuống trang của bạn bởi vì nó load trong khi DOM đang được build. Tuỳ chọn tốt nhất là sử dụng các file ngoài với `async` hoặc `defer` để tránh blocking DOM. Tuỳ chọn khác là đặt các script vào trong  `<head>`. Hầu hết thời gian phân tích code hoặc các script nhỏ là cần thiết trước khi DOM lấy để thực thi chính.

    *Cách làm:*
    > Đảm bảo tất cả các file được load sử dụng `async` hoặc `defer` và quyết định một các hợp lý các code cần được thêm vào `<head>`.

     * 📖 [11 Tips to Optimize JavaScript and Improve Website Loading Speeds](https://www.upwork.com/hiring/development/11-tips-to-optimize-javascript-and-improve-website-loading-speeds/)

* [ ] **Non-blocking JavaScript:** ![high] Các file JavaScript được load asynchronously sử dụng `async` or deferred sử dụng `defer`.

    ```html
    <!-- Defer Attribute -->
    <script defer src="foo.js"></script>

    <!-- Async Attribute -->
    <script async src="foo.js"></script>
    ```

    *Tại sao:*
    > Các khối JavaScript bình thường parse của HTML document, vì vậy khi parser tới một thẻ `<script>` (đặc biệt bên trong `<head>`), nó dừng fetch và chạy nó. Thêm `async` hoặc `defer` được đánh giá cao nếu script của bạn được đặt ở đầu trang nhưng ít giá trị hơn nếu trước thẻ `</body>`. Nhưng thực tết tốt là luôn sử dụng các thuộc tính này để tránh bất kỳ vấn đề hiệu suất nào

    *Cách làm:*
    > ⁃ Thêm `async` (nếu dựa trên các script khác) hoặc `defer` (nếu script dựa vào một script async) giống như một thuộc tính đến thẻ script của bạn. <br>
    ⁃ Nếu bạn có các script nhỏ, có thể sử dụng trên 1 dòng script thay vì ở trên async script.

    * 📖 [Remove Render-Blocking JavaScript](https://developers.google.com/speed/docs/insights/BlockingJS)
    * 📖 [Defer loading JavaScript](https://varvy.com/pagespeed/defer-loading-javascript.html)

* [ ] **Tối ưu và cập nhật các thư viện JS:** ![medium] Tất cả các thư viện JavaScript đã sử dụng trong dự án của bạn là cần thiết (prefer Vanilla JavaScript cho các tính năng đơn giản), được cập nhật phiên bản mới nhất của chúng và không đặt Javascript với nhiều hàm không cần thiết.

    *Tại sao:*
    > Hầu hết thời gian, các phiên bản mới đi kèm với tối ưu hóa và sửa chữa bảo mật. Bạn nên sử dụng code được tối ưu hóa nhất để tăng tốc dự án của mình và đảm bảo rằng bạn sẽ không làm chậm trang web hoặc ứng dụng của mình mà không có plugin lỗi thời. 
    
    *Cách làm:*
    > Nếu dự ánh sử dụng các package NPM, [npm-check](https://www.npmjs.com/package/npm-check) là một thư viện khá thú vị để nâng cấp / cập nhật thư viện của bạn.
    > [Greenkeeper](https://greenkeeper.io/) có thể tự động tìm kiếm các phụ thuộc của bạn và đề xuất thời gian cập nhật mỗi phiên bản mới.
    * 📖 [You may not need jQuery](http://youmightnotneedjquery.com/)
    * 📖 [Vanilla JavaScript for building powerful web applications](https://plainjs.com/)

- [ ] **Kiểm tra kích thước giới hạn của các phụ thuộc:** ![low] Đảm bảo sử dụng các thư viện bên ngoài, hầu hết thời gian, bạn có thể sử dụng thư viện nhẹ hơn cho cùng một chức năng.

    *Tại sao:*
    > Bạn có thể bị cám dỗ sử dụng một trong 745 000 các package bạn  có thể tìm trên [npm](https://www.npmjs.com/), nhưng bạn cần phải chọn package tốt nhất cho nhu cầu của bạn. Ví dụ, MomentJS là một thư viện tuyệt vời nhưng với rất nhiều phương thức bạn không bao giờ có thể sử dụng đó là ý do vì sao Day.js được tạo ra. Với 2kB và 16.4kB cho Moment.

    *Cách làm:*
    > Luôn so sánh và chọn thư viện tốt nhất và nhẹ hơn cho nhu cầu của bạn. Bạn cũng có thể sử dụng các công cụ như [npm trends](http://www.npmtrends.com/) để so sánh số lượng NPM package tải xuống hoặc   [Bundlephobia](https://bundlephobia.com/) để biết kích thước của các phụ thuộc của bạn.

    * 🛠 [ai/size-limit: Prevent JS libraries bloat. If you accidentally add a massive dependency, Size Limit will throw an error.](https://github.com/ai/size-limit)
    * 🛠 [webpack-bundle-analyzer - npm](https://www.npmjs.com/package/webpack-bundle-analyzer)
    * 📖 [Size Limit: Make the Web lighter — Martian Chronicles, Evil Martians’ team blog](https://evilmartians.com/chronicles/size-limit-make-the-web-lighter)

- [ ] **JavaScript Profiling:** ![medium] Kiểm tra các vấn đề hiệu năng trong các tệp JavaScript của bạn (và CSS cũng vậy).

    *Tại sao:*
    > JavaScript phức tạp có thể làm chậm hiệu năng thời gian chạy. Việc xác định các vấn đề có thể có này là điều cần thiết để cung cấp trải nghiệm người dùng mượt mà nhất.

    *Cách làm:*
    > Sử dụng công cụ Timeline trong Chrome Developer Tool để đánh giá các sự kiện script và tìm thấy sự kiện có thể mất quá nhiều thời gian.

     * 📖 [Speed Up JavaScript Execution  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/rendering-tools/js-execution)
    * 📖 [JavaScript Profiling With The Chrome Developer Tools — Smashing Magazine](https://www.smashingmagazine.com/2012/06/javascript-profiling-chrome-developer-tools/)
    * 📖 [How to Record Heap Snapshots  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/memory-problems/heap-snapshots)
    * 📖 [Chapter 22 - Profiling the Frontend - Blackfire](https://blackfire.io/docs/book/22-frontend-profiling)
    * 📖 [30 Tips To Improve Javascript Performance](http://www.monitis.com/blog/30-tips-to-improve-javascript-performance/)

- [ ] **Sử dụng các Service Worker:** ![medium] Bạn đang sử dụng Service Worker trong PWA của bạn để lưu trữ dữ liệu hoặc thực hiện các tác vụ nặng có thể mà không ảnh hưởng đến trải nghiệm người dùng của ứng dụng của bạn.
   
    * 📖 [Service Workers: an Introduction  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/primers/service-workers/)
    * 📖 [Measuring the Real-world Performance Impact of Service Workers  |  Web  |  Google Developers](https://developers.google.com/web/showcase/2016/service-worker-perf)
    * 📖 [What Are Service Workers and How They Help Improve Performance](https://www.keycdn.com/blog/service-workers/)
    * 📹 [How does a service worker work? - YouTube](https://www.youtube.com/watch?v=__xAtWgfzvc)

**[⬆ back to top](#table-of-contents)**

## Server

![server-side]

- [ ] ** Website của bạn đang sử dụng HTTPS:** ![high] 

    *Tại sao:*
    > HTTPS không chỉ dành cho các trang web thương mại điện tử mà còn cho tất cả các trang web đang trao đổi dữ liệu. Dữ liệu được chia sẻ bởi người dùng hoặc dữ liệu được chia sẻ với một thực thể bên ngoài. Các trình duyệt hiện đại giới hạn chức năng cho các trang web không an toàn. Ví dụ: định vị địa lý, thông báo đẩy và nhân viên dịch vụ không hoạt động nếu cá thể của bạn không sử dụng HTTPS. Và ngày nay, việc thiết lập dự án với chứng chỉ SSL dễ dàng hơn nhiều so với trước đây (và cho miễn phí, cảm ơn đến [Let's Encrypt](https://letsencrypt.org/)).

 * 📖 [Why Use HTTPS? | Cloudflare](https://www.cloudflare.com/learning/security/why-use-https/)
 * 📖 [Enabling HTTPS Without Sacrificing Your Web Performance - Moz](https://moz.com/blog/enabling-https-without-sacrificing-web-performance)
 * 📖 [How HTTPS Affects Website Performance](https://wp-rocket.me/blog/https-affects-website-performance/)
 * 📖 [HTTP versus HTTPS versus HTTP2 - The real story | Tune The Web](https://www.tunetheweb.com/blog/http-versus-https-versus-http2/)
 * 📖 [HTTP vs HTTPS — Test them both yourself](https://www.httpvshttps.com/)

- [ ] ** Kích thước trang < 1500 KB (lý tưởng < 500 KB):** ![high] Giảm kích thước trang của bạn + tài nguyên nhiều nhất có thể.

    *Tại sao:*
    > Lý tưởng nhất là bạn nên cố gắng đạt mục tiêu <500 KB nhưng trạng thái web cho thấy trung bình của Kilobyte là khoảng 1500 KB (ngay cả trên thiết bị di động). Tùy thuộc vào người dùng mục tiêu của bạn, kết nối mạng, thiết bị, điều quan trọng là phải giảm càng nhiều càng tốt Kilobyte của bạn để có trải nghiệm người dùng tốt nhất có thể.

    *Cách làm:*
    > ⁃ Tất cả các quy tắc bên trong Front-End Performance Checklist sẽ giúp bạn giảm càng nhiều càng tốt tài nguyên và code của bạn.

    * 📖 [Page Weight](https://httparchive.org/reports/page-weight#bytesTotal)
    * 🛠 [What Does My Site Cost?](https://whatdoesmysitecost.com/)
    * 🛠 [web - Measure full page size in Chrome DevTools - Stack Overflow](https://stackoverflow.com/questions/38239980/measure-full-page-size-in-chrome-devtools)

- [ ] **Thời gian tải trang < 3 giây:** ![high] Giảm thời gian tải trang càng nhiều càng tốt để phân phối nội dung của bạn nhanh chóng tới người dùng của bạn.

    *Tại sao:*
    > Nhanh hơn trang web hoặc ứng dụng của bạn, bạn càng ít có khả năng tăng việc bị quay trở lại, nói cách khác, bạn ít làm mất người dùng hoặc khách hàng trong tương lai. Đã có đủ các nghiên cứu về chủ đề này chứng minh quan điểm đó.
    
    *Cách làm:*
    > Sử dụng các công cụ online như [Page Speed Insight](https://developers.google.com/speed/pagespeed/insights/) hoặc [WebPageTest](https://www.webpagetest.org/) để phân tích những gì có thể làm chậm bạn và Front-End Performance Checklist để cải thiện thời gian tải của bạn.

    * 🛠 [Compare your mobile site speed](https://www.thinkwithgoogle.com/feature/mobile/)
    * 🛠 [Test Your Mobile Website Speed and Performance - Think With Google](https://testmysite.thinkwithgoogle.com/intl/en-us)
    * 📖 [Average Page Load Times for 2018 - How does yours compare? - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/average-page-load-times-websites-2018/)

- [ ] **Thời gian byte đầu tiên < 1.3 giây:** ![high] Giảm thiểu thời gian mà trình duyệt của bạn đợi trước khi nhận dữ liệu.

    * 📖 [What is Waiting (TTFB) in DevTools, and what to do about it](https://scaleyourcode.com/blog/article/27)
    * 📖 [Monitoring your servers with free tools is easy](https://scaleyourcode.com/blog/article/7)
    * 📖 [Time to First Byte (TTFB)](https://varvy.com/pagespeed/ttfb.html)
    * 🛠 [Global latency testing tool](https://latency.apex.sh)

* [ ] **Kích thước Cookie:** ![medium] Nếu bạn đang sử dụng cookies, hãy chắc chắn rằng mỗi cookie không vượt quá 4096 byte và tên miền của bạn không có nhiều hơn 20 cookie.

    *Tại sao:*
    > Cookie được trao đổi trong header HTTP giữa các máy chủ web và trình duyệt. Điều quan trọng là phải giữ kích thước cookie càng thấp càng tốt để giảm thiểu tác động đến thời gian phản hồi của người dùng.

    *Cách làm:*
    > Loại bỏ các cookie không cần thiết

    * 📖 [Cookie specification: RFC 6265](https://tools.ietf.org/html/rfc6265)
    * 📖 [Cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
    * 🛠 [Browser Cookie Limits](http://browsercookielimits.squawky.net/)
    * 📖 [Website Performance: Cookies Don't Taste So Good - Monitis Blog](http://www.monitis.com/blog/website-performance-cookies-dont-taste-so-good/)
    * 📖 [Google's Web Performance Best Practices #3: Minimize Request Overhead - GlobalDots Blog](https://www.globaldots.com/googles-web-performance-best-practices-3-minimize-request-overhead/)

- [ ] **Giảm thiểu các request HTTP:** ![high] Luôn đảm bảo rằng mọi file được yêu cầu đều cần thiết cho trang web hoặc ứng dụng của bạn
 * 📖 [Combine external CSS](https://varvy.com/pagespeed/combine-external-css.html)
 * 📖 [Combine external JavaScript](https://varvy.com/pagespeed/combine-external-javascript.html)

- [ ] **Sử dụng một CDN để chuyển các asset của bạn** ![medium] Sử dụng một CDN để chuyển nhanh hơn nội dung trên toàn thế giới.

 * 📖 [10 Tips to Optimize CDN Performance - CDN Planet](https://www.cdnplanet.com/blog/10-tips-optimize-cdn-performance/)
 * 📖 [HTTP Caching  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching)

- [ ] **Đưa ra các file từ cùng một giao thức:** ![high] Tránh để trang web của bạn đưa ra file từ nguồn bằng cách sử dụng HTTP trên trang web của bạn đang sử dụng HTTPS chẳng hạn. Nếu trang web của bạn đang sử dụng HTTPS, các tệp bên ngoài phải đến từ cùng một giao thức.

- [ ] **Đưa ra các file có thể tiếp cận được:** ![high] Tránh request các file không thể truy cập (404).
 * 📖 [How to avoid bad requests](https://varvy.com/pagespeed/avoid-bad-requests.html)

- [ ] **Thiết lập  HTTP cache headers properly:** ![high] Đặt header HTTP để tránh số lượng vòng lặp cao giữa trình duyệt và máy chủ của bạn.
 * 📖 [Using cache-control for browser caching](https://varvy.com/pagespeed/cache-control.html)

- [ ] **Bật các nén GZIP /:** ![high] Sử dụng phương pháp nén như Gzip hoặc Brotli để giảm kích thước tệp JavaScript của bạn. Với tệp kích thước nhỏ hơn, người dùng sẽ có thể tải xuống nội dung nhanh hơn, dẫn đến hiệu suất được cải thiện.

 * 🛠 [Check GZIP compression](https://checkgzipcompression.com/)
 * 🛠 [Check Brotli Compression](https://tools.keycdn.com/brotli-test)
 * 📖 [Can I use... Brotli](https://caniuse.com/#feat=brotli)

**[⬆ back to top](#table-of-contents)**

---
## Performances và các JS Framework

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
