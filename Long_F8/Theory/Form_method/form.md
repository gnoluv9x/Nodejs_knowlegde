Mặc định form luôn gửi đi với method = GET nếu thẻ form không khai báo method.
    - app.method quy định method được định tuyến. Mặc định thì trình duyệt luôn gửi req dạng GET nhưng app.get sẽ định tuyến tuyến đường mà trình duyệt tới. Tương tự đối với app.post, app.put...

    - Khi submit form nó sẽ được gửi đi với method="" và routing tới action=""
    - Lưu ý: nếu sau khi submit form được gửi đi với một phương thước ko phải là GET
        thì khi reload lại trang các req sẽ luôn được gửi đi với phương thức đó.
        * Khi submit form thì query parameter sẽ được gửi đi kèm
        * Submit được gửi đi với query parameter dưới dạng object có:
            key = name được định nghĩa trong thẻ input
            value = giá trị ô input



        