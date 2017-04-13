# AutoWrapTextView
自动换行解决中英文文本排版TextView

# 使用方法

布局

```
 <com.free.autowraptextview.widget.AutoWrapTextView
        android:id="@+id/awtextview"
        android:layout_width="200dp"
        android:layout_height="wrap_content"
        android:layout_marginTop="20dp"
  />
```
        
public class MainActivity extends AppCompatActivity {

    private String text = "密码：jokG5456KL542356jsjdherGHS";

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        ((AutoWrapTextView) findViewById(R.id.awtextview)).setText(text);

    }
}
