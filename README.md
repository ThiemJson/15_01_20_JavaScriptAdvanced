# B1
Cũng không có gì căng lắm, chỉ là tôi học một tí cái JS nâng cao thôi, thôi chưa hoàn thành khóa Expess, MasterCSS, nhưng mà cảm thấy mình có thể học đồng thời được thì cứ học thôi, bỏ phí thời gian làm gì nhỉ lD 
Lest GOO

# B2 Var let const, 
Đúc kết lại những gì đã học về sự khác biệt giữa Var, Let, Const ; 
- Var có hoisting,  Let và Const không có
Hoisting là gì, các câu lệnh khai báo, (declare) cái biến đó sẽ được đẩy lên đầu trương trình (đối với var thì sẽ đẩy lên đầu cái function scope của nó );
 Còn Let và const thì không 
 Let và Const thì tuân theo Block Scope, Var thì tuân theo Function scope.  Let và Const không thể khai bái lại, còn Var thì có thê khai bái lại, 
 Chung quy thì dùng Let, Const thay Var, và bản thân mình đã không dùng Var từ khá là lâu rồi :D 

 # B3 Function Context and Bind 
 vừa rồi mình gặp một cái khái niệm mới, CONTEXT, nó là cái vẹo gì thế nhỉ > Hmmm  
 Cái này dễ bị nhầm lẫn với nhau khi sử dụng this trong thực tế, 
 ví dụ như là dùng cái This khi sử dụng một cái method của hàm khác, cái this nó sẽ thay đổi, 
 và trong đó mình phải dùng hàm bind 
 Ví dụ: mouse.sayHi.bind(mouse); bind trong này là mình gán lại this này trở lại cái Obj đúng của nó :D 
 Hiểu như vậy chấc là cũng ok lắm rồi nhỉ :D 

 # B4 
 Mình vừa học cái Arr function . mà công nhận có nhiều cái về Arr function mà mình không rõ mặc dù mình dùng nó khác là nhiều lần rồi : 
 - Nó không có context, nghĩa là nếu gọi this một cái đối tượng nào  trong cái arrfunction đó thì sẽ là cái this của thằng gần (thằng cha gần nhất của thằng function đó)
 - và mình cũng biết thêm cái let that = this, rồi bind(that) hoặc bind this cũng đươnc. 
 công nhận CodersX giảng dễ hiểu thật  sự :D 

 
 