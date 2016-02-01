# ButterKnifeDemo
ButterKnife 的使用

1 在build.gradle文件中加上

compile 'com.android.support:appcompat-v7:22.2.1'

2 在Activity中（注入）

@Bind(R.id.MainTextView)  TextView mainTextView;

上面这句的效果相当于
TextView mainTextView = (TextView)findViewById(R.id.MainTextView);

3 在onCreate方法中添加 （绑定）

 ButterKnife.bind(this);
