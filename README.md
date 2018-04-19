# demo-reactJs
Demo build source with rejactJs

Các phần mềm cần thiết:
- Node JS
- Editor: Sublime, VScode, Atom, ...
- Git for Windown
- npm : NPM là chương trình quản lý gói của Node JS

Các package bắt buộc có: 
- Gulp
Đây là một gói dành cho node js, bạn có thể sử dụng gulp hoặc grunt để viết một builder, về phía tôi, tôi lựa chọn gulp.

- Browserify
Với node js bạn có thể chia dự án thành nhiều module nhỏ, tương tự như là C# hay Java, khi cần cái gì mình sẽ import nó vào. Tuy nhiên, node js chỉ có ở phía server side, còn phía client side không có sẵn. Browserify sẽ mang đến tính năng này cho phía client side.

- JSX
Nói cách đơn giản nhất (nhưng không hoàn toàn đúng về bản chất), JSX là cách bạn viết HTML trong file javascript.

Cài đặt các module vào dự án:
1. Tạo folder chứa dự án và chạy node tại folder đó
Tạo một thư mục, sau đó mở "Git base here".

2. Cài đặt gulp global
Gulp global bạn chỉ cần cài một lần bằng lệnh:

npm install gulp --global
Sau khi cài đặt, kiểm tra version của gulp:

gulp -v
Với người dùng trên Mac OS hay Linux, bạn sẽ cần quyền root để cài gulp global, khi đó lệnh sẽ là

sudo npm install gulp --global
Hãy bỏ qua các khái niệm CLI hay thắc mắc gulp global là gì, hãy cứ tiếp tục.

3. Cài đặt các module cần thiết vào dự án
npm install react gulp gulp-react gulp-browserify

4. Kiểm tra các module
Hãy xem lại folder bai-01, hiện tại nó đã có thư mục node_modules, trong thư mục đó có chứa các thư mục con là:

gulp
react
gulp-react
gulp-browserify
Như vậy đã cài đặt xong 4 modules cần thiết.

Tìm hiểu kĩ hơn tại: https://wiki.itvina.com/hoc-react-js-bai-01-xay-dung-builder-cho-du-an-react/
