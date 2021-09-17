npm install prettier
- Thêm dòng sau vào trong file pagekage.json mục "start" :

"beautiful": "prettier --single-quote --tab-width 4 --trailing-comma all --write src/**/*.{js,json,scss}",

    Thêm các thuộc tính bằng cách --thuoc-tinh value
    Một số thuộc tính thông dụng: https://prettier.io/docs/en/options.html

        --print-width 80 : dãn dòng 80 ký tự
        --tab-width 4 : khoảng cách 1 tab

Thực thi: npm run beautiful


