# first
activity的生命周期
##核心代码
```
public class First_Activity extends AppCompatActivity {
    public static final String TAG="MainActivity";
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        Log.d(TAG,"OnCreat");
        setContentView(R.layout.first_layout);
    }

    @Override
    protected void onStart() {
        super.onStart();
        Log.d(TAG,"OnStart");
    }

    @Override
    protected void onPostResume() {
        super.onPostResume();
        Log.d(TAG,"OnResume");
    }

    @Override
    protected void onPause() {
        super.onPause();
        Log.d(TAG,"OnPause");
    }

    @Override
    protected void onStop() {
        super.onStop();
        Log.d(TAG,"OnStop");
    }

    @Override
    protected void onRestart() {
        super.onRestart();
        Log.d(TAG,"OnRestart");
    }

    @Override
    protected void onDestroy() {
        super.onDestroy();
        Log.d(TAG,"OnDestroy");
    }
}
```
# 运行截图 

1.进入软件
![](https://github.com/1061823154/first/blob/master/photo/68747470733a2f2f696d672d626c6f672e6373646e696d672e636e2f32303139303331363231333133353835392e706e67.png)

2.home键退出
![](https://github.com/1061823154/first/blob/master/photo/68747470733a2f2f696d672d626c6f672e6373646e696d672e636e2f32303139303331363231333731393136342e706e67.png)

3.再进入软件![](https://github.com/1061823154/first/blob/master/photo/68747470733a2f2f696d672d626c6f672e6373646e696d672e636e2f32303139303331363231333735333538312e706e67.png)

4.关闭软件![](https://github.com/1061823154/first/blob/master/photo/68747470733a2f2f696d672d626c6f672e6373646e696d672e636e2f32303139303331363231333831383332352e706e67.png)



