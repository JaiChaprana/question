<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".view.auth.PhoneLoginActivity"
    android:background="@drawable/jahdjashk"
    >

    <LinearLayout
        android:id="@+id/toolbar"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:padding="15dp"
        android:orientation="horizontal"
        >
        <TextView
            android:layout_width="0dp"
            android:layout_weight="1"
            android:gravity="center_horizontal"
            android:layout_height="wrap_content"
            android:layout_marginStart="15dp"
            android:textStyle="bold"
            android:textColor="#041260"
            android:textSize="16sp"
            android:text="Enter your phone number"/>
        <ImageButton
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:background="@android:color/transparent"
            android:src="@drawable/ic__baseline_more_vert_24"
            />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:gravity="center_horizontal"
        android:padding="20dp"
        android:orientation="vertical">
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:gravity="center_horizontal"
            android:textColor="#041053"
            android:textStyle="bold"
            android:text="Gossip will send a SMS to verify your phone number. What's my number?"/>
        <Spinner
            android:layout_width="200dp"
            android:layout_height="wrap_content"
            android:prompt="@string/cambodia"
            />
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center_horizontal"
            android:orientation="horizontal">
            <TextView
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:textSize="16sp"
                android:textColor="#FBFBFB"
                android:text="+"/>
            <EditText
                android:id="@+id/username"
                android:layout_width="50dp"
                android:layout_height="wrap_content"
                android:textColor="#041053"
                android:gravity="end"
                android:hint="@string/_855"/>
            <EditText
                android:layout_width="200dp"
                android:layout_height="wrap_content"
                android:textColor="#041053"
                android:hint="@string/phone_number" />
        </LinearLayout>

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textSize="16sp"
            android:layout_marginTop="15dp"
            android:text="Extra SMS charge may apply"/>
    </LinearLayout>
</RelativeLayout>
