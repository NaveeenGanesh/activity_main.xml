<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity"
    android:background="@drawable/cupcake">


    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginEnd="8dp"
        android:layout_marginLeft="8dp"
        android:layout_marginRight="8dp"
        android:layout_marginStart="8dp"
        android:text="Purchase Successful!"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        tools:layout_editor_absoluteY="74dp"
        tools:textSize="30dp" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="wrap_content"
        android:layout_height="81dp"
        android:layout_marginLeft="8dp"
        android:layout_marginStart="8dp"
        android:text="Your order will be delivered shortly,
kindly pay the amount on delivery
Thank you, visit Cake Factory again!"
        app:layout_constraintStart_toStartOf="parent"
        tools:layout_editor_absoluteY="152dp"
        tools:textSize="20dp" />
</android.support.constraint.ConstraintLayout>
