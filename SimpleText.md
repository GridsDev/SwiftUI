Inter Active

ContentView ทำหน้าที่ประกาศเนื้อหาใน Application ผ่านโครงสร้าง struct

struct ContentView: View {
    var body: some View {
        Text("Hello, Looser!")
    }
}

ContentView_Previews ทำหน้าที่สร้าง view ที่มีตัวอย่าง instance จาก struct ContentView ข้างบน

struct ContentView_Previews: PreviewProvider {
    static var previews: some View {
        ContentView()
    }
}
