# Android Custom-Button(With Animation)

xml:

```xml
<Button
    android:id="@+id/btn"
    android:layout_width="@dimen/btn_width"
    android:layout_height="@dimen/btn_height"
    android:background="@drawable/btn_background"
    android:text="@string/btn"
    **android:textColor="@color/white"**
    **android:visibility="invisible"** />
```

kotlin(Activity):

```kotlin
btn.visibility = View.VISIBLE
btn.animation = AnimationUtils.loadAnimation(this, R.anim.btn_appearing)
```

an example:
https://github.com/Waoap/Type-Writer/releases/tag/example
