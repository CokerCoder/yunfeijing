# Hello there 👋

```java
class Me {

    private static Me me = new Me();
    
    String name = "Yunfei Jing";
    String nickName = "Neo";
    String location = "Melbourne";

    private Me() {};
    
    public static Me getMe() {
        return me;
    }
    
    public int getAge() {
        return Calendar.getInstance().get(Calendar.YEAR) - 1999;
    }
    
}
```
