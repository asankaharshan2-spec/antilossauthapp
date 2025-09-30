<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:orientation="vertical" android:gravity="center"
    android:layout_width="match_parent" android:layout_height="match_parent"
    android:padding="24dp">
    <ImageView
        android:layout_width="100dp"
        android:layout_height="100dp"
        android:src="@drawable/ic_antilos_app"
        android:contentDescription="App icon"/>
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="AntiLoss (prototype)"
        android:textSize="18sp"
        android:layout_marginTop="12dp"/>
    <Button
        android:id="@+id/btnEnroll"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Enroll device"
        android:layout_marginTop="16dp"/>
    <Button
        android:id="@+id/btnTerms"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Terms & Privacy"
        android:layout_marginTop="8dp"/>
</LinearLayout>
