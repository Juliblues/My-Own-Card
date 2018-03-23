# My-Own-Card
Google Scholarship 1st Exercise
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">
    <ImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:src="@drawable/androidcard"
        android:scaleType="centerCrop"/>

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:gravity="center"
        android:textSize="24sp"
        android:textStyle="bold"
        android:layout_margin="32dp"
        android:textColor="#D32F2F"
        android:text="So proud of you both, Babe and Pipa!"/>
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_above="@id/keepcoding"
        android:textColor="#FFC107"
        android:textSize="24sp"
        android:textStyle="bold"
        android:layout_marginLeft="48dp"
        android:text="You girls take a breath"/>
    <TextView
        android:id="@+id/keepcoding"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:gravity="center"
        android:layout_above="@id/fromjuliblues"
        android:textSize="24sp"
        android:textStyle="bold"
        android:layout_marginBottom="16dp"
        android:textColor="#2196F3"
        android:text="and keep coding!" />
    <TextView
        android:id="@+id/fromjuliblues"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_alignParentRight="true"
        android:textSize="20sp"
        android:textStyle="bold"
        android:layout_marginRight="48dp"
        android:layout_marginBottom="16dp"
        android:textColor="#4CAF50"
        android:text="From, Juliblues"
        />

</RelativeLayout>
