# Bài test tuyển dụng vị trí Android Developer

### Bài test số 1.
- Link thiết kết : 
  https://www.figma.com/file/mDtLpRdZMhKg5wjL7YzEpm/Bài-test-tuyển-dụng
#### Yêu cầu.
- Làm như file thiết kế màn hình thị trường.
#### Các api cần lấy
- Lấy thông tin thị trường
  Gộp 2 api  <br />
    https://raw.githubusercontent.com/Quangminhs/vps-android-test/master/getlistbaseworldindex.json  <br />
    https://raw.githubusercontent.com/Quangminhs/vps-android-test/master/getlistindexdetail.json <br />
  Chart của các mã thị trường được lấy theo api  <br />
    https://raw.githubusercontent.com/Quangminhs/vps-android-test/master/getchartdataotherindex-{Mã index}.json <br />
    VD: https://raw.githubusercontent.com/Quangminhs/vps-android-test/master/getchartdataotherindex-DJFUTURE.json  <br />
    
- Lấy biến động thị trường 
  Api lấy thông tin chung  <br />
    https://raw.githubusercontent.com/Quangminhs/vps-android-test/master/getpsalldatalsnapshot.json  <br />
  Api lấy chart biến động thị trương <br />
    https://raw.githubusercontent.com/Quangminhs/vps-android-test/master/getchart-{Mã HĐ}.json  <br />
    VD: https://raw.githubusercontent.com/Quangminhs/vps-android-test/master/getchart-vn30f2206.json  <br />
    
    
 - Lấy độ sâu thị trường <br />
   Api màu vẽ chart xanh: <br /> https://raw.githubusercontent.com/Quangminhs/vps-android-test/master/getps10pricesnapshot-B.json  <br />
   API vẽ chart đỏ: <br /> https://raw.githubusercontent.com/Quangminhs/vps-android-test/master/getps10pricesnapshot-S.json  <br />
 
  
    
