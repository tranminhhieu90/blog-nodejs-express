I- Express là 1 framework của nodejs
npm install express
II - Nodemon và debug
Nodemon và 1 thư viện: dùng để tự đông reload node application
npm i nodemon --save-dev
thêm vào file package.json
"start": "nodemon index.js"

nếu dùng để debug mở devtool
"start": "nodemon --inspect index.js"

III - Install morgan
HTTP request logger middleware for node.js ( thư viên logger lại các HTTP request )
