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
 * 🛠 [Sitespeed.io - chào mừng bạn đến với thế giới web tuyệt đẹp](https://www.sitespeed.io/)
 * 🛠 [Calibre](https://calibreapp.com/)
 * 🛠 [Website Speed Test | Kiểm tra hiệu suất của web &raquo; Dotcom-Tools](https://www.dotcom-tools.com/website-speed-test.aspx)
 * 🛠 [Giám sát thời gian hoạt động của website và máy chủ - Pingdom](https://www.pingdom.com/product/uptime-monitoring/) ([Free Signup Link](https://www.pingdom.com/free))
 * 🛠 [Uptime Robot](https://uptimerobot.com)
 * 🛠 [SpeedCurve: Giám sát hiệu suất của Front-end](https://speedcurve.com)
 * 🛠 [PWMetrics - công cụ CLI và thư viện thu thập các số liệu về hiệu suất](https://github.com/paulirish/pwmetrics)
 * 🛠 [Varvy - Tối ưu tốc độ trang]( https://varvy.com/pagespeed/)
 * 🛠 [Lighthouse - Google]( https://developers.google.com/web/tools/lighthouse/#devtools)
 * 🛠 [Checkbot browser extension - Các phương pháp hay nhất về kiểm thử hiệu suất trang web](https://www.checkbot.io/)
 * 🛠 [Yellow Lab Tools | Kiểm tra để giúp tăng tốc các trang web nặng](https://yellowlab.tools/)

### Tài liệu tham khảo

 * 📹 [Giá trị của Javascript - YouTube](https://www.youtube.com/watch?v=_bzqF05xsC4) ([text version](https://medium.com/@addyosmani/the-cost-of-javascript-in-2018-7d8950fbb5d4))
 * [AddyOsmani.com - Ngân sách để bắt đầu cải thiện hiệu suất](https://addyosmani.com/blog/performance-budgets/)
 * 📖 [Bắt đầu với phân tích hiệu suất theo thời gian |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/)
 * 📖 [Trạng thái của 1 website | 2018_01_01](https://httparchive.org/reports/state-of-the-web?start=2018_01_01)
 * 📖 [Dung lượng của một trang web không quan trọng](https://www.speedshop.co/2015/11/05/page-weight-doesnt-matter.html)
 * 📖 [Front-End Performance Checklist 2018 [PDF, Apple Pages]](https://www.smashingmagazine.com/2018/01/front-end-performance-checklist-2018-pdf-pages/)
 * 📖 [Thiết kế đáp ứng hiệu xuất cân bằng giữa Thẩm mỹ và Tốc độ - By Lara Callender Hogan [eBook, Print]](http://designingforperformance.com/index.html)
 * 📖 [Varvy - Bảng thuật ngữ về hiệu suất cho website](https://varvy.com/performance/)
 * 📖 [fabkrum/web-performance-resources: Cập nhật bộ sưu tập tài nguyên có giá trị về hiệu suất website](https://github.com/fabkrum/web-performance-resources)
 * 📖 [Checkbot -Các phương pháp hay nhất về tối ưu tốc độ web](https://www.checkbot.io/guide/speed/)
 * 🛠 [Progressive Tooling - Danh sách các công cụ bên thứ ba được xây dựng bởi cộng đồng có thể sử dụng được để cải thiện hiệu suất trang](https://progressivetooling.com/)

---

## HTML

![html]

- [ ] **Tối giản HTML:** ![medium] The HTML code là tối giản, các comment, khoảng trắng và các dòng mới phải loại bỏ khỏi các file trên bản production.

    *Tại sao:*
    > Xóa toàn bộ những khoảng trống, comment, và dòng trống không cần thiết sẽ giảm được kích thước HTML của bạn và tăng tốc thời gian tải trang của bạn và rõ ràng  việc tải xuống cho user của bạn được giảm nhẹ hơn.
    
    *Làm như nào:*
    > Hầu hết các framework đều có plugin tạo điều kiện cho việc tối giản hóa các trang web. Bạn có thể sử dụng một loạt các module NPM mà có thể làm công việc đó cho bạn một cách tự động.

    * 🛠 [Tối giản HTML | Tối giản Code](http://minifycode.com/html-minifier/)
    * 🛠 [Nén HTML online](http://refresh-sf.com)
    * 📖 [Thử nghiệm về nén HTML — Perfection Kills](http://perfectionkills.com/experimenting-with-html-minifier/#use_short_doctype)

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
    > Các thuộc tính type đã không còn cần thiết vì HTML5 đã ngầm hiểu text/css và text/javascript như các giá trị mặc định. Phần code không được sử dụng nên được loại bỏ vì nó làm trang nặng hơn khi không được sử dụng bởi website hoặc ứng dụng của bạn.
     
    *Làm như nào:*
    > ⁃ Chắc chắn là tất cả các thẻ `<link>` và `<script>` của bạn không có bất kì thuộc tính type nào.

    * 📖 [Thẻ Script | CSS-Tricks](https://css-tricks.com/the-script-tag/)
   
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

- [ ] **Giảm thiểu số lượng jframe:** ![high] Chỉ sử dụng iframe nếu bạn không có bất cứ một công nghệ khác. Cố gắng tránh việc sử dụng jframe nhiều nhất có thể.

**[⬆ quay về đầu trang](#table-of-contents)**

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
    > ⁃ Sử dụng công cụ online hoặc bất kì một plugin nào đó trước hoặc trong khi xây dựng hoặc phát triển của bạn để ghép nối các file lại với nhau. <br>
    ⁃ Đương nhiên là hãy chắc chắn việc ghép nối không phá vỡ project của bạn.

    * 📖 [HTTP: Tối ưu hóa việc phân phối các ứng dụng - High Performance Browser Networking (O'Reilly)](https://hpbn.co/optimizing-application-delivery/#optimizing-for-http2)
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

- [ ] **CSS Không sử dụng:** ![medium] Xóa các selector CSS không sử dụng

    *Vì sao:*
    > Loại bỏ các selector CSS không được sử dụng có thể giảm kích thước các file của bạn và tăng tốc độ load nội dung lên.

    *Làm như nào:*
    > ⁃ ⚠️ Hãy luôn luôn kiểm tra nếu framework CSS bạn muốn sử dụng không chứa code chuẩn hóa/reset. Thỉnh thoảng bạn không cần mọi thứ đặt ở trong file reset/chuẩn hóa.
    

    * 🛠 [UnCSS Online](https://uncss-online.com/)
    * 🛠 [PurifyCSS](https://github.com/purifycss/purifycss)
    * 🛠 [PurgeCSS](https://github.com/FullHuman/purgecss)
    * 🛠 [Chrome DevTools Coverage](https://developers.google.com/web/updates/2017/04/devtools-release-notes#coverage)

* [ ] **CSS quan trọng:** ![high] Phần CSS quan trọng (hoặc "trong màn hình đầu tiên") thu thập tất cả các CSS được sử dụng để render ra phần hiển thị của trang. nó được nhúng trước phần gọi CSS chính của bạn và nằm giữa `<style></style>` trên một dòng duy nhất (tối giản nếu có thể).
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

- [ ] **Định dạng Webfont:** ![medium] Bạn đang sử dụng WOFF2 trên project web hay ứng dụng của bạn.

    *Vì sao:*
    > Theo Google, định dạng nén WebFont WOFF 2.0 cung cấp mức tăng trung bình khoảng 30% so với WOFF 1.0. Thật tuyệt vời khi sử dụng WOFF 2.0, WOFF 1.0 như biện pháp dự phòng và TFF.

    *Làm như nào:*
    > Hãy kiểm tra trước khi mua một font mới mà nhà cung cấp đã đưa cho bạn định dạng WOFF2. Nếu bạn sử dụng font miễn phí, bạn luôn luôn có thể sử dụng Font Squirrel để chuyển sang mọi định dạng bạn cần.

    * 📖 [WOFF 2.0 – Tìm hiểu về định dạng font web thế hệ tiếp theo và convert từ TTF sang WOFF2](https://gist.github.com/sergejmueller/cf6b4f2133bcb3e2f64a)
    * 🛠 [Tạo bộ @font-face Kits cho riêng bạn » Font Squirrel](https://www.fontsquirrel.com/tools/webfont-generator)
    * 🛠 [IcoMoon App - Tạo ra Icon Font, SVG, PDF & PNG](https://icomoon.io/app/)
    * 📖 [Sử dụng @font-face | CSS-Tricks](https://css-tricks.com/snippets/css/using-font-face/?ref=frontendchecklist)
    * 📖 [Liệu tôi có thể sử dụng... WOFF2](https://caniuse.com/#feat=woff2)

- [ ] **Sử dụng `preconnect` để load font của bạn nhanh hơn:** ![medium]

    ```html
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    ```

    *Vì sao:*
    > Khi bạn tới một trang web, thiết bị của bạn cần tìm hiểu nơi mà trang web của bạn đang hoạt động và nó cần kết nối tới server nào. Trình duyệt của bạn phải liên lạc với DNS server và chờ nó tìm xong trước khi tìm và tải tài nguyên (font, file CSS,...) Việc tìm nạp và kết nối trước cho phép trình duyệt tìm kiếm các thông tin về DNS và bắt đầu thiết lập kết nối TCP tới server lưu trữ file font. Điều này giúp hiệu suất tăng lên bởi vì khi trình duyệt  phân tích file css với thông tin về font và phát hiện nó cần yêu cầu file font từ server, nó sẽ có sẵn thông tin về DNS và có kết nối mở đến server sẵn trong pool.

    *Làm như nào:*
    > ⁃ Trước khi tìm nạp trước các webfont của bạn, sử dụng webpagetest để đánh giá website của bạn <br>
    ⁃ Tìm kiếm, tra cứu DNS và lưu máy chủ đang được yêu cầu <br>
    ⁃ Tìm nạp trước các webfont của bạn trong thẻ `<head>` và thêm các tên máy chủ mà bạn đã tìm nạp cuối cùng

    * 📖 [Đẩy nhanh việc tải về Google Font bằng kết nối trước - CDN Planet](https://www.cdnplanet.com/blog/faster-google-webfonts-preconnect/)
    * 📖 [Giúp trang web của bạn nhanh hơn với các gợi ý về kết nối | Viget](https://www.viget.com/articles/make-your-site-faster-with-preconnect-hints/)
    * 📖 [Các hướng dẫn cuối cùng về gợi ý cho trình duyệt: Tải trước, Nạp trước, và  kết nối trước - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/guide-to-browser-hints-preload-preconnect-prefetch/)
    * 📖 [Hướng dẫn toàn diện về chiến lược tải font —zachleat.com](https://www.zachleat.com/web/comprehensive-webfonts/#font-face)
    * 🛠 [typekit/webfontloader: Trình tải font cho phép bạn thêm quyền quản lý khi sử dụng font được liên kết thông qua @font-face.](https://github.com/typekit/webfontloader)

- [ ] **Kích thước của Webfont:** ![medium] Các kích thước của Webfont không được  vượt quá 300kb (bao gồm tất cả các biến thể)

 * 📖 [Font Bytes - Page Weight](https://httparchive.org/reports/page-weight#bytesFont)

- [ ] **Chặn Flash hoặc các text bị ẩn:** ![medium] Tránh các loại text màu trong suốt trong quá trình Webfont được tải.

 * 📖 [`font-display` cho các khối](https://css-tricks.com/font-display-masses/)
 * 📖 [CSS font-display:Tương lai của việc render font trên Web](https://www.sitepoint.com/css-font-display-future-font-rendering-web/)

**[⬆ quay lại đầu trang](#table-of-contents)**

## Images

![images]

 * 📖 [Image Bytes in 2018](https://httparchive.org/reports/page-weight#bytesImg)

* [ ] **Tối ưu hóa hình ảnh:** ![high] Các hình ảnh của bạn phải được tối ưu, được nén mà không ảnh hưởng trực tiếp tới user cuối.

    *Vì sao:*
    > Việc tối ưu hóa các hình ảnh sẽ tải nhanh hơn trên trình duyệt của bạn và tiêu thụ ít dữ liệu hơn
    
    *Làm như nào:*
    
    > ⁃ Cố gắng sử dụng các hiệu ứng trên CSS3 khi có thể (thay cho các ảnh nhỏ) <br>
    ⁃ Khi có thể, hãy sử dụng font thay cho phần text được mã hóa trong ảnh của bạn <br>
    ⁃ Sử dụng SVG
    ⁃ Sử dụng một công cụ và chỉ định mức độ nén dưới 85.
    
    * 📖 [Tối ưu hóa hình ảnh | Các nguyên tắc cơ bản về Web | Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization)
    * 📖 [Tối ưu hóa các hình ảnh cần thiết - Một eBook của Addy Osmani](https://images.guide/)
    * 🛠 [TinyJPG – Nén các hình ảnh JPEG một cách thông minh](https://tinyjpg.com/)
    * 🛠 [Kraken.io - Tối ưu hóa hình ảnh online](https://kraken.io/web-interface)
    * 🛠 [Compressor.io - Tối ưu hóa, nén các hình ảnh JPEG và PNG](https://compressor.io/compress)
    * 🛠 [Cloudinary - Công cụ phân tích hình ảnh](https://webspeedtest.cloudinary.com)
    * 🛠 [SVGOMG - Tối ưu hóa các file vector SVG](https://jakearchibald.github.io/svgomg/)


* [ ] **Các định dạng hình ảnh:** ![high] .Chọn định dạng hình ảnh của bạn một cách thích hợp.

    *Vì sao:*
    > Để chắc chắn các hình ảnh của bạn không làm website chậm đi, hãy chọn định dạng tương ứng với ảnh của bạn. Nếu nó là là một bức ảnh, JPEG hầu như phù hợp hơn PNG hay GIF. Nhưng đừng quên xem qua các thế hệ định dạng tiếp theo mà nó có thể giảm kích thước file của bạn. Mỗi định dạng ảnh đều có ưu điểm và nhược điểm riêng, điều quan trọng là phải biết chúng để đưa ra sự lựa chọn tốt nhất.

    *Làm như nào:*
    > ⁃ Sử dụng [Lighthouse](https://developers.google.com/web/tools/lighthouse/) để xác định hình ảnh cuối cùng có thể sử dụng **định dạng ở thế hệ tiếp theo** (như JPEG 2000m, JPEG XR hay WebP) <br>
    ⁃ So sánh các định dạng khác nhau, thông thường sử dụng PNG8 thì tốt hơn PNG16, nhưng thỉnh thoảng lại không.

    * 📖 [Lựa chọn hình ảnh ở các thế hệ tiếp theo  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/lighthouse/audits/webp)
    * 📖 [Định dạng hình ảnh phù hợp cho trang web của bạn là gì? — SitePoint](https://www.sitepoint.com/what-is-the-right-image-format-for-your-website/)
    * 📖 [PNG8 - Chiến thắng cuối cùng — SitePoint](https://www.sitepoint.com/png8-the-clear-winner/)
    * 📖 [8-bit vs 16-bit - Độ sau màu nào bạn nên sử dụng và tại sao - DIY Photography](https://www.diyphotography.net/8-bit-vs-16-bit-color-depth-use-matters/)

- [ ] **Sử dụng các hình ảnh vector thay cho raster/bitmap:** ![medium] Thay thế việc sử dụng hình ảnh vector cho các hình ảnh dạng bitmap (khi có thể).

    *Vì sao:*
    > Các ảnh vector (SVG) có xu hướng nhỏ hơn các ảnh thông thường và SVG đã có khả năng responsive, co dãn một cách hoàn hảo. Các hình ảnh này hoàn toàn có thể tạo và chỉnh sửa bằng CSS.
    
* [ ] **Kích thước của các hình ảnh:** ![medium] Đặt các thuộc tính `width` và `height` vào thẻ `<img>` nếu kích thước cuối cùng của hình ảnh sau khi render đã được biết trước.

    *Vì sao:*
    
    > Nếu chiều cao và chiều rộng được đặt, đã có phần không gian yêu cầu cho hình ảnh đã được đặt riêng khi tải trang.  nhiên, nếu không có các thuộc tính này, trình duyệt không s được kích thước của ảnh và không thể dự trữ không gian thích hợp cho nó. Hiệu ứng sau đó sẽ là bố cục trang bị thay đổi trong khi tải (trong khi tải ảnh).
    
* [ ] **Tránh việc sử dụng hình ảnh Base64:** ![medium] Cuối cùng thì bạn có thể chuyển đổi các ảnh nhỏ sang dạng base64 nhưng nó thực sự không phải là phương pháp hay.

    * 📖 [Mã hóa và hiệu năng của Base64, Phần 1 và 2 của Harry Roberts](https://csswizardry.com/2017/02/base64-encoding-and-performance/)
    * 📖 [Một cái nhìn rõ ràng hơn về hiệu năng của ảnh dạng Base64 – The Page Not Found Blog](http://www.andygup.net/a-closer-look-at-base64-image-performance/)
    * 📖 [Khi nào thì nên mã hóa base64 (và khi nào thì không) | David Calhoun](https://www.davidbcalhoun.com/2011/when-to-base64-encode-images-and-when-not-to/)
   * 📖 [Mã hóa hình ảnh bằng base64 để các trang nhanh hơn | Các yếu tố về hiệu năng và seo](https://varvy.com/pagespeed/base64-images.html)

* [ ] **Lazy loading:** ![medium] Các hình ảnh trên màn hình được tải một cách lười biếng. (Một noscript fallback luôn được cung cấp sẵn). 

    *Vì sao:*
    > It will improve the response time of the current page and then avoid loading unnecessary images that the user may not need.
    > Nó sẽ cải thiện được thời gian trả về của trang hiện tại và sau đó tránh tải nhũng hình ảnh không cần thiết mà user có thể không cần tới.
    *Làm như nào:*
    > ⁃ Sử dụng [lighthouse](https://developers.google.com/web/tools/lighthouse/) để xác định có bao nhiêu **hình ảnh trên màn hình**. <br>
    ⁃ sử dụng plugin Javascript như sau để thực hiện việc lazyload các hình ảnh của bạn. Hãy chắc chắn là chỉ có những hình ảnh trên màn hình. <br>
    ⁃Ngoài ra, hãy đảm bảo lazyload chỉ tải xuống các hình ảnh thay thế và được hiển thị khi di chuột qua hoặc các hành động khác của người dùng.

    * 🛠 [verlok/lazyload: GitHub](https://github.com/verlok/lazyload)
    * 🛠 [aFarkas/lazysizes: GitHub](https://github.com/aFarkas/lazysizes/)
    * 📖 [Lazy Loading các hình ảnh và Video  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/lazy-loading-guidance/images-and-video/)
    * 📖 [5 cách tuyệt vời để tải hình ảnh qua lazyload giúp tải trang nhanh hơn - Dynamic Drive Blog](http://blog.dynamicdrive.com/5-brilliant-ways-to-lazy-load-images-for-faster-page-loads/)

* [ ] **Responsive các hình ảnh:** ![medium] Hãy đảm bảo là những hình ảnh được cung cấp khá gần với kích thước hiển thị của bạn.

    *Vì sao:*
    > Các thiết bị nhỏ không cần những hình ảnh lớn hơn so với khung nhìn của họ. Bạn nên có nhiều phiên bản của một hình ảnh trên nhiều kích thước khác nhau.
    
    *Làm như nào:*

    > Tạo ra các kích thước khác nhau của hình ảnh để các thiết bị của bạn trỏ tới. <br>
    ⁃ Sử dụng `srcset` và `picture` để phân phối nhiều biến thể của mỗi hình ảnh.
    
     * 📖 [Responsive các hình ảnh - Tìm hiểu về phát triển web | MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

**[⬆ quay lại đầu trang](#table-of-contents)**

## JavaScript

![javascript]

- [ ] **Giảm thiểu JS:** ![high] Tất cả các file Javascript đều phải tối giản, các comments, khoảng trắng và dòng trống đều phải được loại bỏ khỏi các file của production. *(Vẫn hợp lệ nếu sử dụng HTTP/2)*.

    *Vì sao:*
    > xóa toàn bộ các khoảng trống, comments và xuống dòng không cần thiết sẽ giảm được kích thước các file Javascript của bạn và tăng tốc tải trang và giảm nhẹ được dung lượng user tải về.
    
    *Làm như nào:*
    > ⁃ Sử dụng các công cụ được đề xuất bên dưới để tối giản các file của bạn tự động trước hoặc trong khi bạn xây dựng hay phát triển.

    * 🛠 [uglify-js - npm](https://www.npmjs.com/package/uglify-js)
    * 🛠 [Nén code Javascript online](http://refresh-sf.com)
    * 📖 [Short read: HTTP/2 có gì khác? Chúng ta vẫn nên rút gọn và ghép code hay không?](https://scaleyourcode.com/blog/article/28)

* [ ] **Không có Javascript dạng Inline:** ![medium] *(Chỉ phù hợp các trang web)* Tránh việc nhúng nhiều code Javascript ở giữa thẻ body của bạn. Nhóm code Javascript của bạn lại trong một file bên ngoài hoặc nằm cuối cùng của thẻ `<head>` hay đặt nó ở cuối trang (trước thẻ `<body>`).

    *Vì sao:*
    >  Việc đặt Javascript nhúng trực tiếp vào thẻ `<body>` của bạn có thể làm chậm trang vì nó phải tải trong khi DOM đang được xây dựng. Tùy chọn tốt nhất là sử dụng một file bên ngoài với `async` hay `defer` để không chặn DOM lại. Một cách khác là đặt các đoạn script trong thẻ `<head>` của bạn. Hầu hết thời gian để phân tích code hawojc các đoạn script nhỏ cần được tải trước khi DOM thực hiện tiến trình chính.
    *Làm như nào:*
    > Đảm bảo là mọi file của bạn đề sử dụng `async` hoặc `defer` và đưa ra một quyết định tốt nhất cho việc bạn phải đưa code của mình vào thẻ `<head>`.

     * 📖 [11 Mẹo nhỏ để tối ưu code Javascript và cải thiện tốc độ load trang](https://www.upwork.com/hiring/development/11-tips-to-optimize-javascript-and-improve-website-loading-speeds/)

* [ ] **Non-blocking JavaScript:** ![high] Các file Javascript được load bất đồng bộ sử dụng `async` hoặc ngưng lại bằng cách sử dụng thuộc tính `defer`.

    ```html
    <!-- Defer Attribute -->
    <script defer src="foo.js"></script>

    <!-- Async Attribute -->
    <script async src="foo.js"></script>
    ```

    *Vì sao:*
    > Javascript chặn việc phân tích thông thường của tài liệu HTML, vì vậy khi trình phân tích tiếp cận thẻ `<script>` (đặc biệt là bên trong thẻ `<head>`), nó dừng lại để nạp và thực thi. Việc thêm `async` hoặc `defer` được đánh giá cao nếu các script của bạn được đặt trên cùng của trang nhưng ít giá trị hơn nếu nó chỉ nằm trước thẻ `</body>`. Nhưng thực tế thì tốt nhất vẫn nên sử dụng các thuộc tính này để tránh ảnh hưởng xấu nên hiệu suất.
    
    *Làm như nào:*
    > ⁃ Thêm `async` (nếu script này không phụ thuộc vào script khác) hoặc `defer` (nếu script này phụ thuộc vào phần trên hoặc phụ thuộc vào script bất đồng bộ khác) như nột thuộc tính đối với thẻ script của bạn <br>
    ⁃ Nếu bạn có những đoạn script nhỏ, có thể sử dụng script dạng inline được đặt ở trên các script bất đồng bộ.
    
    * 📖 [Loại bỏ Render-Blocking JavaScript](https://developers.google.com/speed/docs/insights/BlockingJS)
    * 📖 [Trì hoãn việc tải Javascript](https://varvy.com/pagespeed/defer-loading-javascript.html)

* [ ] **Tối ưu và nâng cấp thư viện Javascript:** ![medium] All JavaScript libraries used in your project are necessary (prefer Vanilla JavaScript for simple functionalities), updated to their latest version and don't overwhelm your JavaScript with unnecessary methods.


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
