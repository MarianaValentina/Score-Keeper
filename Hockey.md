# Score-Keeper

<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:layout_margin="15dp"
    android:background="@drawable/hockey"
    android:alpha="0.6"
    tools:context="com.example.android.scorekeeper.MainActivity">


    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:orientation="vertical">

            <TextView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="team 1"
                android:textAllCaps="true"
                android:textSize="32sp"
                android:fontFamily="sans-serif-black"
                android:textAlignment="center"
                android:textColor="#00802b"/>

            <TextView
                android:id="@+id/first_team_score"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:fontFamily="sans-serif"
                android:text="0"
                android:textAlignment="center"
                android:textColor="#00802b"
                android:textSize="72sp" />

            <Button
                android:id="@+id/first_team_five_points_button"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Try\n Penalty Try"
                android:textAlignment="gravity"
                android:layout_gravity="center"
                android:onClick="AddFivePointsTeamOne"
                android:background="#00b33c"
                android:alpha="0.8"
                android:padding="10dp"
                android:layout_marginBottom="24dp"/>

            <Button
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Penalty \n drop goals"
                android:textAlignment="gravity"
                android:layout_gravity="center"
                android:onClick="AddThreePointsTeamOne"
                android:background="#00b33c"
                android:alpha="0.8"
                android:padding="10dp"
                android:layout_marginBottom="24dp"/>

            <Button
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Conversion"
                android:textAlignment="gravity"
                android:layout_gravity="center"
                android:onClick="AddTwoPointsTeamOne"
                android:background="#00b33c"
                android:alpha="0.8"
                android:padding="10dp"
                android:layout_marginBottom="24dp"/>


        </LinearLayout>

        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:orientation="vertical">

            <TextView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="team 2"
                android:textAllCaps="true"
                android:textSize="32sp"
                android:fontFamily="sans-serif-black"
                android:textAlignment="center"
                android:textColor="#00802b"/>

            <TextView
                android:id="@+id/second_team_score"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="0"
                android:textAlignment="center"
                android:textSize="72sp"
                android:fontFamily="sans-serif"
                android:textColor="#00802b"/>

            <Button
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_gravity="center"
                android:onClick="AddFivePointsTeamTwo"
                android:text="Try\n Penalty Try"
                android:textAlignment="gravity"
                android:background="#00b33c"
                android:alpha="0.8"
                android:padding="10dp"
                android:layout_marginBottom="24dp"/>

            <Button
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Penalty \n drop goals"
                android:textAlignment="gravity"
                android:layout_gravity="center"
                android:onClick="AddThreePointsTeamTwo"
                android:background="#00b33c"
                android:alpha="0.8"
                android:padding="10dp"
                android:layout_marginBottom="24dp"/>

            <Button
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Conversion"
                android:textAlignment="gravity"
                android:layout_gravity="center"
                android:onClick="AddTwoPointsTeamTwo"
                android:background="#00b33c"
                android:alpha="0.8"
                android:padding="10dp"
                android:layout_marginBottom="24dp"/>
        </LinearLayout>
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <Button
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="reset score"
            android:onClick="ResetScore"
            android:background="#00b33c"
            android:alpha="0.8"
            android:padding="10dp"
            android:layout_marginTop="24dp"
            android:layout_marginLeft="15dp"
            android:layout_marginRight="15dp"/>
    </LinearLayout>

</LinearLayout>
