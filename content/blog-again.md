+++
title = "Lại là blog à !?"
date = 2020-08-01

[taxonomies]
categories = ["blog", "vietnamese"]
tags = ["blog"]
archive = ["2020-08"]
+++

Ừ, đúng là như tiêu đề, đây lại là một Rudo's blog mới.\
"Ơ, vậy nó khác gì cái đã chết đứng trước kia?"\
Hahaha, một câu hỏi rất hay đó.

Chắc để mình nói về lý do tại sao cái blog mới này lại được remake trước đã nhỉ?\
Cái này thực ra cũng rất dễ đoán được nếu bạn nhìn vào cái ngày mình viết bài này.\

2020-08-01.\

Bạn đoán được chưa? Nếu chưa thì để mình nói thẳng luôn là tại
Việt Nam đang lại phải chiến đấu với đợt dịch COVID-19 lần 2 đó. Lúc mình viết bài
này thì Việt Nam cũng đã có tận 2 ca tử vong đầu tiên vì con virus chết tiệt này!<sup>[1](https://vtv.vn/xa-hoi/viet-nam-co-ca-dau-tien-tu-vong-do-dich-covid-19-20200731142655572.htm)[2](https://vnexpress.net/them-mot-benh-nhan-covid-19-tu-vong-4139522.html)</sup>.\
<!-- more -->

Kể ra số mình nó cũng khá đen, đợt vừa hết Tết tháng 2 kia mình còn hớn hở
vào Sài Gòn sớm để đi xin được chỗ thực tập cho học kì đấy thì đùng phát được nghỉ thêm Tết 2 tháng!\
Trong giai đoạn đấy thì trường cũng không phân công chỗ thực tập luôn,
thành ra cuối cùng phải xin vào làm ở một xưởng in 3D, công việc không hề hứng thú tí nào.
(mặc dù học được nhiều thứ hay ho về công nghệ in 3D, cũng như cách vẽ, chỉnh sửa mô hình in, v.v..
nhưng tại vì nó không hợp với mình nên thực sự không hứng thú lắm)

Và khi mình tưởng chừng mọi thứ như thế là xong, thì 2020 lại bảo: "Ê! Mới có hết nửa năm
này thôi!" và làm thêm 1 cú nữa vào mặt, đúng y như lần 1, với cái đợt dịch lần 2 này.\
Lại là chuẩn bị đi xin việc thì lại dịch...\
Hahaha, nghĩ cũng buồn cười khi mà chỉ hai tuần trước mình còn định tới học kì hè này sẽ đi xin chỗ làm khác
tốt hơn. Mà thôi, việc cũng đã xong rồi, ngồi than vãn cũng chả giải quyết được gì.

Thế là thành ra mình có nhiều thời gian rảnh quá, chẳng nhẽ cả cái hè 2 tháng mà không làm cả?
Như thế thì chết quách đi cho xong. Vậy nên là cái blog này mới ra bản remake đó.\
Thật ra mình có ý định remake blog lâu rồi, nhưng thực sự trong đầu không có gì hay ho
để viết mà chia sẻ - đây cũng là lý do cái blog trước chết toi mà chưa kịp làm gì.

Lần này có một vài thay đối lớn nhỏ so với cái blog lần trước, chắc mình cũng liệt kê vài cái
ra cho mọi người dễ hình dung:

## Vấn đề về hosting
Blog lần trước mình dùng một gói blog Wordpress của [z.com](https://z.com/vn/).
Thật ra dịch vụ này rất tốt, lúc đấy mình nhớ mình đăng kí một gói 1 năm của nó bao gồm
hosting và domain dot com 1 năm với giá chỉ 289k!\
Chỉ có một vấn đề lớn là sau năm đầu tiên đó thì họ bắt đầu billing với giá 150k/tháng với dịch
vụ hosting và gia hạn domain dot com kia với giá 900k/năm...
Một cái giá cực kì đắt đỏ với một thú vui viết blog cho sinh viên như mình,
thành ra đó cũng là dấu chấm hết của cái blog kia.

Lần này, blog mới sử dụng hoàn toàn những công cụ open-source, vậy nên nó cũng hoàn toàn miễn phí.
Bạn nào có hứng thú về cách mình tạo blog này thì có thể ngó qua trang [About](@/pages/about.md).
Đúng là so với cái gói hosting wordpress kia thì một cái static site khó có thể đo bì được, nhất là
khi đây là lần đầu tiên mình "chơi" blog kiểu này. Tuy nhiên nếu mà bỏ hẳn được mối lo lắng về tiền
hosting thì mình nghĩ là hoàn toàn đáng.

Về vấn đề hosting hiện tại thì site đang được host trên dịch vụ [Netlify](https://www.netlify.com/)
đơn giản chỉ vì nó có hỗ trợ sử dụng `zola` để build, và có dịch vụ Deploy Review Page (nó tương tự như
chức năng Staging Page của các gói hosting Wordpress) có thể tự trigger từ  các pull-request nên mình khá thích.
Trong tương lai nếu bằng một cách kì diệu nào đó blog phát triển lên thì có thể mình sẽ thuê VPS riêng
hoặc các gói hosting chuyên nghiệp để host blog, nhưng trong tương lai trước mắt thì chắc blog này
sẽ cứ là combo `zola` + `netlify` mà hoạt động thôi.

Chỉ tiếc một điều là cái domain cũ rudoblog.com kia sau khi cái blog kia chết thì nó đã bị chuyển
sang chủ mới, và hiện tại ở thời điểm viết bài thì nó đang ở trang thái clientHold tới tận 2021-01-18,
và cũng không biết được là nó sẽ được gia hạn tiếp hay không.<sup>[3](https://whois.domaintools.com/rudoblog.com)</sup>
Hiện tại mình đang nghiên cứu một vài tên miền khác như dot me, dot tech, dot net để thay cho miền dot com này,
tuy nhiên trong thời gian tương lai gần thì chắc blog sẽ sử dụng sub-domain miễn phí được cho bởi `netlify`
đó là `rudoblog.netlify.com`.

## Vấn đề về content
Cái blog đầu tiên kia mình tạo lúc chỉ mới là sinh viên năm đầu tiên của Đại Học.
Nói thẳng ra là lúc đó còn rất nhiều mơ mộng hão huyền. Haha. Bây giờ vẫn còn mơ mộng nhiều
nhưng đã bỏ được phần "hão huyền" kia rồi. Chắc để nêu một ví dụ đơn giản thì đó là lúc đó
mình viết bài linh ta linh tinh, dịch bài linh tinh từ Dotabuff rồi thêm thắt linh tinh, hoàn toàn
không có mục đích nào rõ ràng. Sau đó thêm các gói SEO này nọ để buff site lên mà không có
content gì hay để chống lưng cho sự phát triển đó. Chỉ sau vài tháng là mình không còn động lực gì.
Bề ngoài thì blog có nhiều lượt view, kể cả người lẫn bot, nhưng bên trong ruột thì nó đã chết rồi.

Lần này, sau 3 năm mình cũng đã có nhiều thay đổi về con người, kể ra cái lớn nhất là mình hoàn toàn
đã bỏ hẳn chơi game như một con nghiện. Cái khoảng thời gian lớn từ việc bỏ game kia cho mình nhiều
thời gian rảnh để làm những việc khác, có thể nói là có ích hơn, như là tìm hiểu về bản thân chính
mình chẳng hạn. (vấn đề này có lẽ sẽ được nói ở một bài khác).
Và lần này mình nghĩ là mình có nhiều content để viết hơn, vừa là về những vấn đề gặp phải của bản thân
như là vấn đề tình cảm (chà, việc này chắc cũng để một bài khác), vấn đề xã hội (chị mình mới cưới vào
hồi đầu tháng 3, và anh rể về sống chung - cái này chắc cũng để một bài khác!) hay các vấn đề linh tinh
khác mà mình muốn viết về nó.

Về trước mắt thì content của blog chắc là mình sẽ viết về một phần mềm TUI Zone Builder cho game
Age of Chaos. Nếu bạn hỏi là tại sao không chơi game nữa mà sao lại ngồi viết phần mềm cho nó thì
đây là một phần mềm tương tự như kiểu Level Editor của các game khác, mình viết phần mềm này chẳng qua
chỉ để sử dụng nó để viết thêm các zone cho game để tập luyện thêm khả năng viết cho mình mà thôi.
Mình dự là sẽ viết 2 bài/1 tuần về vấn đề này, nhưng cũng có thể chỉ ra được 1 bài/1 tuần như
[Factorio Friday Fact - FFF](https://factorio.com/blog/) hay thậm chí là chậm hơn tùy vào mức độ lười
của mình, haha.

## Vấn đề về branding
Vấn đề cuối cùng của cái blog trước kia đó là mình trước kia muốn quảng cáo cái blog kia, muốn nó
thành một cái branding cho riêng bản thân. Điều này thực sự không phù hợp với một blog cá nhân mà
thỉnh thoảng mình mới viết content và không có sự đầu tư lớn cho các content này.
Lần này mình sẽ dẹp hẳn toàn bộ mấy thứ rắc rối, lằng nhằng và thực dụng đó.
Blog mới này hoàn toàn sẽ tập trung vào vấn đề cốt lõi đó là nó là một nơi để mình viết những suy
nghĩ của mình, cũng như những thứ mình học được và muốn chia sẻ với mọi người. Thế thôi.
Vì lý do này mà các chức năng của blog về phần tương tác với người đọc sẽ khá hạn chế, ví dụ như hoàn
toàn không có chức năng comment hay liên hệ người viết là mình (nếu bạn muốn liên hệ mình thì xin mời
ngó qua trang [About](@/pages/about.md)), cũng như không có chức năng chia sẻ bài qua mạng xã hội, v.v..
Toàn bộ các chức năng của blog sẽ chỉ có mục đích là hỗ trợ mình viết bài. Thế thôi, không hơn, không kém.
Về cách theo dõi bài viết nếu bạn có hứng thú với content thì blog có chức năng tạo RSS feed, bạn có thể
dùng nó để theo dõi các bài viết của mình. Mình sẽ nghiên cứu chức năng mail subscriber sau nếu có thời gian
và các bạn có nhu cầu.

## Chốt hạ
Chà, dài dòng loằng ngoằng giải thích lý do lý trấu nhiêu vậy thôi nhỉ.\
Bản TLDR của bài này đơn giản là blog sống lại một lần nữa rồi đó.\
Hẹn các bạn ở các bài lần sau.
