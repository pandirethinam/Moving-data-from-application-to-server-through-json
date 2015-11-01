# Moving-data-from-application-to-server-through-json
Move data from apps to server
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical" >

    <TextView
        android:id="@+id/tvIsConnected"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center_horizontal"
        android:background="#FF0000"
        android:textColor="#FFF"
        android:textSize="18dp"
        android:layout_marginBottom="5dp"
        android:text="is connected?" />

    <RelativeLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content">

        <TextView
            android:id="@+id/tvName"
            android:layout_width="50dp"
            android:layout_height="wrap_content"
            android:text="Name"
            android:layout_alignBaseline="@+id/etName"/>
        <EditText
            android:id="@+id/etName"
            android:layout_width="150dp"
            android:layout_height="wrap_content"
            android:layout_toRightOf="@+id/tvName"/>
        <TextView
            android:id="@+id/tvCountry"
            android:layout_width="50dp"
            android:layout_height="wrap_content"
            android:layout_below="@+id/tvName"
            android:text="Country"
            android:layout_alignBaseline="@+id/etCountry"/>
        <EditText
            android:id="@+id/etCountry"
            android:layout_width="150dp"
            android:layout_height="wrap_content"
            android:layout_toRightOf="@+id/tvCountry"
            android:layout_below="@+id/etName"/>
        <TextView
            android:id="@+id/tvTwitter"
            android:layout_width="50dp"
            android:layout_height="wrap_content"
            android:layout_below="@+id/tvCountry"
            android:text="Twitter"
            android:layout_alignBaseline="@+id/etTwitter"/>
        <EditText
            android:id="@+id/etTwitter"
            android:layout_width="150dp"
            android:layout_height="wrap_content"
            android:layout_toRightOf="@+id/tvTwitter"
            android:layout_below="@+id/etCountry"/>

    </RelativeLayout>

    <Button
        android:id="@+id/btnPost"
        android:layout_width="200dp"
        android:layout_height="wrap_content"
        android:layout_gravity="center_horizontal"
        android:text="POST"/>

</LinearLayout>
