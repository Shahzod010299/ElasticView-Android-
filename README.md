# ElasticView-Android

implementation 'com.github.armcha:ElasticView:0.2.0'


<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <io.armcha.elasticview.ElasticView
        android:id="@+id/elasticView"
        android:layout_width="match_parent"
        android:layout_height="200dp"
        app:cardCornerRadius="10dp"
        app:cardElevation="5dp"
        android:layout_centerInParent="true"
        android:layout_marginHorizontal="30dp">
        <TextView
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:text="ElasticView"
            android:gravity="center"
            android:textSize="40sp"
            android:textColor="@color/black"
            android:textStyle="bold"/>
    </io.armcha.elasticview.ElasticView>

</RelativeLayout>
