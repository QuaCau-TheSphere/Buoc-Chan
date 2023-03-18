digraph "masterGraph"{
overlap=false
T [ label="Công việc sau\nchuyến đi" fontsize = 30 fontname="SVN-Avo" shape="plaintext" ]	// Không dùng label mà dùng plain note cho tiêu đề sơ đồ vì như thế tiêu đề sẽ luôn ở trên đầu mà không ở vùng giữa trang, vừa tốn chỗ mà cũng không đẹp bằng (đặc biệt là ở neato) 
//NODES
//====================
node [ shape=plaintext style="filled, rounded" fontname="SVN-Avo" margin=0.2 fillcolor="#c6cac3"]
node [ shape="circle" fixedsize=true width=.8 fillcolor="#81b29a" fontcolor="#000000" ]
Nhật [ image="./Nhật.png" label="\n\n\n\n\nNhật" ]
Tuyên
Ân
Mỹ
Trang
Thảo
Nhung

node [ shape=polygon fixedsize=false style="filled, rounded" fontname="SVN-Avo" margin=0.2 fillcolor="#c6cac3" ] 

"Làm phiếu lượng giá" 
"Hỏi nhu cầu của mọi người về bài truyền thông và bài thu hoạch" [ label="Hỏi nhu cầu của\nmọi người về bài\ntruyền thông và\nbài thu hoạch" ]
"Làm thư cảm ơn" 
"Làm quà lưu niệm" 
"Lên nội dung báo cáo qua văn bản" [label="Lên nội dung báo cáo\nqua văn bản"]
"Lên nội dung báo cáo qua đồ hoạ thông tin" [label="Lên nội dung báo cáo\nqua đồ hoạ thông tin"]
"Lên nội dung báo cáo trên web" [label="Lên nội dung báo cáo\ntrên web"]

edge [len=1.5 penwidth=7 arrowhead=none style=tapered]
Nhật -> {"Lên kế hoạch chung", "Chăm Cubi", "Kỹ thuật" }
Tuyên -> {"Lên kế hoạch chung", "Báo cáo với Hải Đăng" }
Ân -> {"Lên nội dung báo cáo qua văn bản", "Lên kế hoạch chung", "Chăm Cubi" }
Mỹ -> {"Lên kế hoạch chung"}
Trang -> {"Lên kế hoạch truyền thông", "Truyền thông" }
Nhung -> {"Lên kế hoạch truyền thông", "Truyền thông" }
Thảo -> {"Thiết kế"}
}
