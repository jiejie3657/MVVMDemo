MVVM在iOS应用的Demo，主要通过TableView来演示

MVVMDemo的架构



Model: 数据的模型

View: 其实包括View和ViewController两部分，统称为View

ViewModel: 本Demo，主要是处理网络请求，把获取的数据显示在TableView上

另外

TableViewProtocol: 为了避免ViewController太重，我把TableView的DataSource和Delegate分离出来
