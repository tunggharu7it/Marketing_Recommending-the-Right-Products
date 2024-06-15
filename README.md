# Marketing Recommending the Right Products

Bộ dữ liệu bao gồm 541,909 bản ghi và 8 cột. Dưới đây là một cái nhìn tổng quan về mỗi cột:
1.	InvoiceNo: Đây là một cột dữ liệu kiểu object chứa số hóa đơn cho mỗi giao dịch. Mỗi số hóa đơn có thể đại diện cho nhiều mặt hàng được mua trong một giao dịch duy nhất.
2.	StockCode: Một cột dữ liệu kiểu object đại diện cho mã sản phẩm cho mỗi mặt hàng.
3.	Description: Cột này, cũng là một cột dữ liệu kiểu object, chứa các mô tả về các sản phẩm. Nó có một số giá trị bị thiếu, với 540,455 bản ghi không rỗng trên tổng số 541,909.
4.	Quantity: Đây là một cột số nguyên chỉ số lượng sản phẩm được mua trong mỗi giao dịch.
5.	InvoiceDate: Một cột datetime ghi lại ngày giờ của mỗi giao dịch.
6.	UnitPrice: Một cột số thực đại diện cho giá đơn vị của mỗi sản phẩm.
7.	CustomerID: Một cột số thực chứa mã khách hàng cho mỗi giao dịch. Cột này có một số lượng đáng kể giá trị bị thiếu, chỉ có 406,829 bản ghi không rỗng trên tổng số 541,909.
8.	Country: Một cột object ghi lại quốc gia mà mỗi giao dịch đã diễn ra.


## Collaborative Filtering
Xây dựng hệ thống gợi ý dựa trên lọc cộng tác
  
## Content-based recommenders
Xây dựng hệ thống gợi ý dựa trên nội dung
