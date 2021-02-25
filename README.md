<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:orientation="vertical" android:layout_width="match_parent"
    android:layout_height="match_parent">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <ImageView
            android:id="@+id/imageView"
            android:layout_width="40dp"
            android:layout_height="30dp"
            android:layout_margin="10dp"
            android:layout_weight="3"
            app:srcCompat="@drawable/arrow" />

        <TextView
            android:id="@+id/textView"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="10dp"
            android:layout_weight="6"
            android:text="Space Cleanup"
            android:textColor="#0C0C0C"
            android:textSize="20sp"
            android:textStyle="bold" />

        <ImageView
            android:id="@+id/imageView2"
            android:layout_width="5dp"
            android:layout_height="30dp"
            android:layout_margin="10dp"
            android:layout_weight="2"
            android:padding="2dp"
            app:srcCompat="@drawable/settings" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:gravity="center|center_horizontal|center_vertical"
        android:orientation="vertical">

        <TextView
            android:id="@+id/textViewx"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginLeft="70dp"
            android:layout_weight="1"
            android:text="GB"
            android:textStyle="bold" />

    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:gravity="center|center_horizontal|center_vertical"
        android:orientation="vertical">

        <TextView
            android:id="@+id/textView3"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="7.60"
            android:textColor="#0C0C0C"
            android:textSize="50sp"
            android:textStyle="bold" />

    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical">

        <TextView
            android:id="@+id/textView5"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:layout_marginTop="10dp"
            android:layout_weight="1"
            android:gravity="center"
            android:text="View Details >"
            android:textStyle="bold" />
    </LinearLayout>

    <Button
        android:id="@+id/button5"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center_horizontal"
        android:layout_marginTop="10dp"
        android:layout_marginBottom="10dp"
        android:background="@drawable/roundbutton"
        android:text="Clean up All"
        app:backgroundTint="#37A8F4" />

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <TextView
            android:id="@+id/textView7"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_margin="10dp"
            android:layout_weight="1"
            android:text="Phone Storage"
            android:textColor="#0C0C0C"
            android:textStyle="bold" />

        <TextView
            android:id="@+id/textView8"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_margin="10dp"
            android:layout_weight="1"
            android:text="62% used/44.68 GB available" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="250dp"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <TextView
            android:id="@+id/textView9"
            android:layout_width="wrap_content"
            android:layout_height="2dp"
            android:layout_margin="10dp"
            android:layout_weight="1"
            android:background="#311B92" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <TextView
            android:id="@+id/textView10"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_margin="10dp"
            android:layout_weight="1"
            android:text="Spcific cleanup" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <ImageView
            android:id="@+id/imageView3"
            android:layout_width="30dp"
            android:layout_height="50dp"
            android:layout_margin="5dp"
            android:layout_weight="1"
            app:srcCompat="@drawable/whatsapp" />

        <ImageView
            android:id="@+id/imageView4"
            android:layout_width="30dp"
            android:layout_height="50dp"
            android:layout_margin="5dp"
            android:layout_weight="1"
            app:srcCompat="@drawable/line" />

        <ImageView
            android:id="@+id/imageView5"
            android:layout_width="30dp"
            android:layout_height="50dp"
            android:layout_margin="5dp"
            android:layout_weight="1"
            app:srcCompat="@drawable/box" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <TextView
            android:id="@+id/textView11"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:gravity="center"
            android:text="Whatsapp cleanup"
            android:textColor="#0C0C0C"
            android:textStyle="bold" />

        <TextView
            android:id="@+id/textView12"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:gravity="center"
            android:text="Line cleanup"
            android:textColor="#0C0C0C"
            android:textStyle="bold" />

        <TextView
            android:id="@+id/textView13"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:gravity="center"
            android:text="Photo cleanup"
            android:textColor="#0C0C0C"
            android:textStyle="bold" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <TextView
            android:id="@+id/textVie"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:gravity="center"
            android:text="8.06 GB" />

        <TextView
            android:id="@+id/textVi"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:gravity="center"
            android:text="0GB" />

        <TextView
            android:id="@+id/textV"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:gravity="center"
            android:text="13.06GB" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="10dp"
        android:orientation="horizontal">

        <ImageView
            android:id="@+id/imageView7"
            android:layout_width="30dp"
            android:layout_height="50dp"
            android:layout_margin="5dp"
            android:layout_weight="1"
            app:srcCompat="@drawable/youtube" />

        <ImageView
            android:id="@+id/imageView8"
            android:layout_width="30dp"
            android:layout_height="50dp"
            android:layout_margin="5dp"
            android:layout_weight="1"
            app:srcCompat="@drawable/headphones" />

        <ImageView
            android:id="@+id/imageView9"
            android:layout_width="30dp"
            android:layout_height="50dp"
            android:layout_margin="5dp"
            android:layout_weight="1"
            app:srcCompat="@drawable/duplicate" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <TextView
            android:id="@+id/text1"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:gravity="center"
            android:text="Video cleanup"
            android:textColor="#0C0C0C"
            android:textStyle="bold" />

        <TextView
            android:id="@+id/text2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:gravity="center"
            android:text="Audio cleanup"
            android:textColor="#0C0C0C"
            android:textStyle="bold" />

        <TextView
            android:id="@+id/text3"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:gravity="center"
            android:text="Duplicate Files"
            android:textColor="#0C0C0C"
            android:textStyle="bold" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <TextView
            android:id="@+id/textView14"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:gravity="center"
            android:text="17.65 GB" />

        <TextView
            android:id="@+id/textView15"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:gravity="center"
            android:text="2.37 GB" />

        <TextView
            android:id="@+id/textView16"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:gravity="center" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="horizontal">

        <TextView
            android:id="@+id/textView17"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_margin="10dp"
            android:layout_weight="1"
            android:text="In Depth Cleanup" />
    </LinearLayout>

</LinearLayout>
