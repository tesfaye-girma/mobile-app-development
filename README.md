# mobile-app-development
layout using xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:orientation="vertical"
    android:layout_width="fill_parent"
    android:layout_height="fill_parent">

    <ScrollView
        android:id="@+id/SCROLLER_ID"
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:scrollbars="vertical"
        android:fillViewport="true">

        <TextView
            android:id="@+id/TEXT_STATUS_ID"
            android:layout_width="fill_parent"
            android:layout_height="fill_parent"
            android:layout_weight="1.0"/>
    </ScrollView>
</LinearLayout>
