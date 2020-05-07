# homepage-
this is the home page of the project
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@android:color/white">


        <androidx.constraintlayout.widget.ConstraintLayout
            android:id="@+id/pageTopContainer"
            android:layout_width="match_parent"
            android:elevation="@dimen/dimen_0dp"
            android:layout_height="0dp"
            android:background="@android:color/white"
            app:layout_constraintHeight_default="percent"
            app:layout_constraintHeight_percent="0.43"
            app:layout_constraintTop_toTopOf="parent">

            <androidx.constraintlayout.widget.ConstraintLayout
                android:id="@+id/constraintLayout2"
                android:elevation="0dp"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                app:layout_constraintTop_toTopOf="parent">

                <ImageView
                    android:layout_width="match_parent"
                    android:layout_height="0dp"
                    android:background="@drawable/main_page_shape"
                    app:layout_constraintHeight_default="percent"
                    app:layout_constraintHeight_percent="0.8"
                    app:layout_constraintTop_toTopOf="parent" />

                <androidx.constraintlayout.widget.ConstraintLayout
                    android:id="@+id/balancesContainer"
                    android:layout_width="match_parent"
                    android:layout_height="0dp"
                    app:layout_constraintHeight_default="percent"
                    app:layout_constraintHeight_percent="0.7"
                    app:layout_constraintTop_toTopOf="parent">
<LinearLayout

    android:background="@drawable/profile_shape"
    android:layout_width="0dp"
    android:layout_height="0dp"
    app:layout_constraintDimensionRatio="1:1"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintTop_toTopOf="parent"
    android:padding="@dimen/dimen_1dp"
    android:layout_marginTop="@dimen/dimen_4dp"
    app:layout_constraintWidth_default="percent"
    app:layout_constraintWidth_percent="0.12">
    <ImageView
        android:id="@+id/id_imgv_open_profil"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:src="@drawable/profile"
        />
</LinearLayout>


                    <ImageView
                        android:id="@+id/privacy_button"
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:layout_marginStart="@dimen/dimen_16dp"
                        android:layout_marginTop="@dimen/dimen_4dp"
                        android:src="@drawable/ic_visibility_off_accent_color_24dp"
                        android:tint="@color/color_gray"
                        app:layout_constraintStart_toStartOf="parent"
                        app:layout_constraintTop_toTopOf="parent" />

                    <androidx.constraintlayout.widget.ConstraintLayout
                        android:id="@+id/hiddenBalance"
                        android:layout_width="0dp"
                        android:layout_height="0dp"
                        android:background="@drawable/circular_shape"
                        app:layout_constraintCircle="@id/balanceDisplayed"
                        app:layout_constraintCircleAngle="110"
                        app:layout_constraintCircleRadius="@dimen/dimen_70dp"
                        app:layout_constraintDimensionRatio="1:1"
                        app:layout_constraintEnd_toEndOf="parent"
                        app:layout_constraintHeight_default="percent"
                        app:layout_constraintHeight_percent="0.6"
                        app:layout_constraintHorizontal_bias="0.858"
                        app:layout_constraintStart_toEndOf="@id/privacy_button"
                        app:layout_constraintTop_toBottomOf="@+id/privacy_button">

                        <ImageView
                            android:id="@+id/hiddenImage"
                            android:layout_width="0dp"
                            android:layout_height="0dp"
                            android:padding="@dimen/dimen_10dp"
                            android:scaleType="centerCrop"
                            android:src="@drawable/mtn_momo"
                            app:layout_constraintDimensionRatio="1:1"
                            app:layout_constraintEnd_toEndOf="parent"
                            app:layout_constraintStart_toStartOf="parent"
                            app:layout_constraintTop_toTopOf="parent"
                            app:layout_constraintWidth_default="percent"
                            app:layout_constraintWidth_percent="0.4" />

                        <ImageView
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:src="@drawable/ic_update_black_24dp"
                            app:layout_constraintBottom_toBottomOf="parent"
                            app:layout_constraintEnd_toEndOf="parent"
                            app:layout_constraintStart_toStartOf="parent" />


                        <TextView
                            android:id="@+id/hiddenAmount"
                            android:layout_width="match_parent"
                            android:layout_height="wrap_content"
                            android:gravity="center"
                            android:text=""
                            android:textSize="@dimen/dimen_15sp"
                            app:layout_constraintBottom_toBottomOf="parent"
                            app:layout_constraintEnd_toEndOf="parent"
                            app:layout_constraintStart_toStartOf="parent"
                            app:layout_constraintTop_toTopOf="parent" />


                    </androidx.constraintlayout.widget.ConstraintLayout>

                    <androidx.constraintlayout.widget.ConstraintLayout
                        android:id="@+id/balanceDisplayed"
                        android:layout_width="0dp"
                        android:layout_height="0dp"
                        android:layout_marginTop="@dimen/dimen_20dp"
                        android:background="@drawable/circular_shape"
                        android:padding="@dimen/dimen_10dp"
                        app:layout_constraintDimensionRatio="1:1"
                        app:layout_constraintEnd_toEndOf="parent"
                        app:layout_constraintHeight_default="percent"
                        app:layout_constraintHeight_percent="0.8"
                        app:layout_constraintHorizontal_bias="0.4"
                        app:layout_constraintStart_toStartOf="parent"
                        app:layout_constraintTop_toTopOf="parent">

                        <ImageView
                            android:id="@+id/displayOperratorImage"
                            android:layout_width="0dp"
                            android:layout_height="0dp"
                            android:padding="@dimen/dimen_4dp"
                            android:scaleType="centerCrop"
                            android:src="@drawable/orangemoney"
                            app:layout_constraintDimensionRatio="1:1"
                            app:layout_constraintEnd_toEndOf="parent"
                            app:layout_constraintStart_toStartOf="parent"
                            app:layout_constraintTop_toTopOf="parent"
                            app:layout_constraintWidth_default="percent"
                            app:layout_constraintWidth_percent="0.25" />
                        <TextView
                            android:layout_width="wrap_content"
                            app:layout_constraintTop_toBottomOf="@+id/displayOperratorImage"
                            android:id="@+id/displayedPhoneNumber"
                            app:layout_constraintStart_toStartOf="parent"
                            android:text="698481557"
                            android:textSize="@dimen/dimen_12sp"
                            app:layout_constraintEnd_toEndOf="parent"
                            android:layout_height="wrap_content"/>

                        <ImageView
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:src="@drawable/ic_update_black_24dp"
                            app:layout_constraintBottom_toBottomOf="parent"
                            app:layout_constraintEnd_toEndOf="parent"
                            app:layout_constraintStart_toStartOf="parent" />


                        <TextView
                            android:id="@+id/displayedAmount"
                            android:layout_width="match_parent"
                            android:layout_height="wrap_content"
                            android:gravity="center"
                            android:text="124 500"
                            android:textSize="@dimen/dimen_20sp"
                            app:layout_constraintBottom_toBottomOf="parent"
                            app:layout_constraintTop_toTopOf="parent" />


                    </androidx.constraintlayout.widget.ConstraintLayout>

                </androidx.constraintlayout.widget.ConstraintLayout>

                <androidx.cardview.widget.CardView
                    android:id="@+id/bockets"
                    android:layout_width="match_parent"
                    android:layout_height="0dp"
                    android:layout_marginHorizontal="@dimen/dimen_8dp"
                    android:elevation="@dimen/dimen_0dp"
                    app:cardCornerRadius="@dimen/dimen_10dp"
                    app:layout_constraintHeight_default="percent"
                    app:layout_constraintHeight_percent="0.3"
                    app:layout_constraintTop_toBottomOf="@+id/balancesContainer">

                    <androidx.constraintlayout.widget.ConstraintLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent"
                        android:orientation="vertical">

                        <LinearLayout
                            android:id="@+id/bars"
                            android:layout_width="match_parent"
                            android:layout_height="0dp"
                            android:padding="1.6dp"
                            android:weightSum="5"
                            app:layout_constraintHeight_default="percent"
                            app:layout_constraintHeight_percent="0.7"
                            app:layout_constraintTop_toTopOf="parent">

                            <androidx.constraintlayout.widget.ConstraintLayout
                                android:layout_width="0dp"
                                android:layout_height="match_parent"
                                android:layout_marginLeft="1dp"
                                android:layout_weight="1">

                                <ProgressBar
                                    style="@style/CustomProgressVerticalTopLeft"
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:foregroundGravity="bottom"
                                    android:progress="0"
                                    android:id="@+id/firstBocketBar"
                                    app:layout_constraintStart_toStartOf="parent" />

                                <TextView
                                    android:id="@+id/firstBocketTitle"
                                    android:layout_width="38dp"
                                    android:layout_height="23dp"
                                    android:text="@string/title_home"
                                    android:textColor="@android:color/white"
                                    android:textSize="@dimen/dimen_15sp"
                                    android:textStyle="bold"
                                    app:layout_constraintBottom_toBottomOf="parent"
                                    app:layout_constraintEnd_toEndOf="parent"
                                    app:layout_constraintStart_toStartOf="parent"
                                    app:layout_constraintTop_toTopOf="parent" />

                                <TextView
                                    android:id="@+id/firsBocketTargetAmount"
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:text="0f"
                                    android:textColor="@android:color/white"
                                    android:textSize="@dimen/dimen_10sp"
                                    app:layout_constraintEnd_toEndOf="parent"
                                    app:layout_constraintStart_toStartOf="parent"
                                    app:layout_constraintTop_toTopOf="parent" />

                                <TextView
                                    android:id="@+id/firsBocketCurentAmount"
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:layout_marginHorizontal="@dimen/dimen_2dp"
                                    android:text="0f"
                                    android:textColor="@android:color/white"
                                    android:textSize="@dimen/dimen_10sp"
                                    app:layout_constraintBottom_toBottomOf="parent"
                                    app:layout_constraintEnd_toEndOf="@+id/firstBocketTitle"
                                    app:layout_constraintStart_toStartOf="@+id/firstBocketTitle" />

                            </androidx.constraintlayout.widget.ConstraintLayout>

                            <androidx.constraintlayout.widget.ConstraintLayout
                                android:layout_width="0dp"
                                android:layout_height="match_parent"
                                android:layout_marginLeft="1dp"
                                android:layout_weight="1"
                                android:background="@color/colorPrimary">

                                <ProgressBar
                                    style="@style/CustomProgressVertical"
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:progress="0"
                                    android:id="@+id/secondBocketBar"
                                     />

                                <TextView
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:text="@string/bill"
                                    android:textColor="@android:color/white"
                                    android:textSize="@dimen/dimen_15sp"
                                    android:textStyle="bold"
                                    android:id="@+id/secondBocketTitle"
                                    app:layout_constraintBottom_toBottomOf="parent"
                                    app:layout_constraintEnd_toEndOf="parent"
                                    app:layout_constraintStart_toStartOf="parent"
                                    app:layout_constraintTop_toTopOf="parent" />

                                <TextView
                                    android:id="@+id/secondBocketTargetAmount"
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:text="0f"
                                    android:textColor="@android:color/white"
                                    android:textSize="@dimen/dimen_10sp"
                                    app:layout_constraintEnd_toEndOf="parent"
                                    app:layout_constraintStart_toStartOf="parent"
                                    app:layout_constraintTop_toTopOf="parent" />

                                <TextView
                                    android:id="@+id/secondBocketCurentAmount"
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:layout_marginHorizontal="@dimen/dimen_2dp"
                                    android:text="0f"
                                    android:textColor="@android:color/white"
                                    android:textSize="@dimen/dimen_10sp"
                                    app:layout_constraintBottom_toBottomOf="parent"
                                    app:layout_constraintEnd_toEndOf="parent"
                                    app:layout_constraintStart_toStartOf="parent" />

                            </androidx.constraintlayout.widget.ConstraintLayout>

                            <androidx.constraintlayout.widget.ConstraintLayout
                                android:layout_width="0dp"
                                android:layout_height="match_parent"
                                android:layout_marginLeft="1dp"
                                android:layout_weight="1"
                                android:background="@color/colorPrimary">

                                <ProgressBar
                                    style="@style/CustomProgressVerticalSecond"
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:progress="0"
                                    android:id="@+id/thirdBocketBar"
                                    />

                                <TextView
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:text="@string/transport"
                                    android:textColor="@android:color/white"
                                    android:textSize="@dimen/dimen_15sp"
                                    android:textStyle="bold"
                                    android:id="@+id/thirdBocketTitle"
                                    app:layout_constraintBottom_toBottomOf="parent"
                                    app:layout_constraintEnd_toEndOf="parent"
                                    app:layout_constraintStart_toStartOf="parent"
                                    app:layout_constraintTop_toTopOf="parent" />

                                <TextView
                                    android:id="@+id/thirdBocketTargetAmount"
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:text="0f"
                                    android:textColor="@android:color/white"
                                    android:textSize="@dimen/dimen_10sp"
                                    app:layout_constraintEnd_toEndOf="parent"
                                    app:layout_constraintStart_toStartOf="parent"
                                    app:layout_constraintTop_toTopOf="parent" />

                                <TextView
                                    android:id="@+id/thirdBocketCurentAmount"
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:layout_marginHorizontal="@dimen/dimen_2dp"
                                    android:text="0f"
                                    android:textColor="@android:color/white"
                                    android:textSize="@dimen/dimen_10sp"
                                    app:layout_constraintBottom_toBottomOf="parent"
                                    app:layout_constraintEnd_toEndOf="parent"
                                    app:layout_constraintStart_toStartOf="parent" />

                            </androidx.constraintlayout.widget.ConstraintLayout>

                            <androidx.constraintlayout.widget.ConstraintLayout
                                android:layout_width="0dp"
                                android:layout_height="match_parent"
                                android:layout_marginLeft="1dp"
                                android:layout_weight="1"
                                android:background="@color/colorPrimary">

                                <ProgressBar
                                    style="@style/CustomProgressVerticalThird"
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:progress="0"
                                    android:id="@+id/fourthBocketBar"
                                    />

                                <TextView
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:text="@string/entertainment"
                                    android:textColor="@android:color/white"
                                    android:textSize="@dimen/dimen_15sp"
                                    android:textStyle="bold"
                                    android:id="@+id/fourthBocketTitle"
                                    app:layout_constraintBottom_toBottomOf="parent"
                                    app:layout_constraintEnd_toEndOf="parent"
                                    app:layout_constraintStart_toStartOf="parent"
                                    app:layout_constraintTop_toTopOf="parent" />

                                <TextView
                                    android:id="@+id/fourthBocketTargetAmount"
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:text="0f"
                                    android:textColor="@android:color/white"
                                    android:textSize="@dimen/dimen_10sp"
                                    app:layout_constraintEnd_toEndOf="parent"
                                    app:layout_constraintStart_toStartOf="parent"
                                    app:layout_constraintTop_toTopOf="parent" />

                                <TextView
                                    android:id="@+id/fourthBocketCurentAmount"
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:layout_marginHorizontal="@dimen/dimen_2dp"
                                    android:text="0f"
                                    android:textColor="@android:color/white"
                                    android:textSize="@dimen/dimen_10sp"
                                    app:layout_constraintBottom_toBottomOf="parent"
                                    app:layout_constraintEnd_toEndOf="parent"
                                    app:layout_constraintStart_toStartOf="parent" />

                            </androidx.constraintlayout.widget.ConstraintLayout>

                            <androidx.constraintlayout.widget.ConstraintLayout
                                android:layout_width="0dp"
                                android:layout_height="match_parent"
                                android:layout_marginLeft="@dimen/dimen_1dp"
                                android:layout_marginRight="1dp"
                                android:layout_weight="1">

                                <ProgressBar
                                    style="@style/CustomProgressVerticalTopRigth"
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:progress="0"
                                    android:id="@+id/fifthBocketBar"
                                    />

                                <TextView
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:text="@string/healt"
                                    android:textColor="@android:color/white"
                                    android:textSize="@dimen/dimen_15sp"
                                    android:textStyle="bold"
                                    android:id="@+id/fifthBocketTitle"
                                    app:layout_constraintBottom_toBottomOf="parent"
                                    app:layout_constraintEnd_toEndOf="parent"
                                    app:layout_constraintStart_toStartOf="parent"
                                    app:layout_constraintTop_toTopOf="parent" />

                                <TextView
                                    android:id="@+id/fifthBocketTargetAmount"
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:text="0f"
                                    android:textColor="@android:color/white"
                                    android:textSize="@dimen/dimen_10sp"
                                    app:layout_constraintEnd_toEndOf="parent"
                                    app:layout_constraintStart_toStartOf="parent"
                                    app:layout_constraintTop_toTopOf="parent" />

                                <TextView
                                    android:id="@+id/fifthBocketCurentAmount"
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:layout_marginHorizontal="@dimen/dimen_2dp"
                                    android:text="0f"
                                    android:textColor="@android:color/white"
                                    android:textSize="@dimen/dimen_10sp"
                                    app:layout_constraintBottom_toBottomOf="parent"
                                    app:layout_constraintEnd_toEndOf="parent"
                                    app:layout_constraintStart_toStartOf="parent" />

                            </androidx.constraintlayout.widget.ConstraintLayout>
                        </LinearLayout>



                            <TextView
                                android:id="@+id/curent_general_amount"
                                android:layout_width="wrap_content"
                                android:layout_height="wrap_content"
                                android:layout_gravity="start"
                                android:layout_marginEnd="@dimen/dimen_5dp"
                                android:layout_weight="1"
                                android:layout_marginStart="@dimen/dim_8dp"
                                app:layout_constraintBottom_toTopOf="@+id/general_progression"
                                app:layout_constraintTop_toBottomOf="@+id/bars"
                                app:layout_constraintStart_toStartOf="parent"
                                android:text="-100.000"
                                android:textColor="@android:color/black"
                                android:textSize="@dimen/dimen_13sp"
                                />

                            <TextView
                                android:id="@+id/general_amount"
                                android:layout_width="wrap_content"
                                android:layout_height="wrap_content"
                                android:layout_marginStart="@dimen/dim_8dp"
                                android:layout_gravity="right"
                                android:layout_marginEnd="@dimen/dimen_5dp"
                                android:layout_weight="1"
                                android:gravity="right"
                                app:layout_constraintBottom_toTopOf="@+id/general_progression"
                                android:text="200.000"
                                app:layout_constraintTop_toBottomOf="@+id/bars"
                                android:textColor="@android:color/black"
                                android:textSize="@dimen/dimen_13sp"
                                app:layout_constraintEnd_toEndOf="parent" />



                        <ProgressBar
                            android:id="@+id/general_progression"
                            style="@style/Widget.AppCompat.ProgressBar.Horizontal"
                            android:layout_width="match_parent"
                            android:layout_height="0dp"
                            android:orientation="horizontal"
                            android:layout_marginHorizontal="@dimen/dimen_8dp"
                            android:progress="40"
                            android:layout_marginBottom="@dimen/dimen_4dp"
                            android:progressTint="@color/colorPrimary"
                            app:layout_constraintBottom_toBottomOf="parent"
                            app:layout_constraintHeight_default="percent"
                            app:layout_constraintHeight_percent="0.1"
                            />


                    </androidx.constraintlayout.widget.ConstraintLayout>

                </androidx.cardview.widget.CardView>
            </androidx.constraintlayout.widget.ConstraintLayout>


        </androidx.constraintlayout.widget.ConstraintLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:id="@+id/contacts_container"
            android:layout_marginVertical="@dimen/dim_8dp"
            app:layout_constraintHeight_default="percent"
            android:gravity="center_horizontal"
            app:layout_constraintHeight_percent="0.12"
            app:layout_constraintTop_toBottomOf="@id/pageTopContainer"
            >
            <androidx.constraintlayout.widget.ConstraintLayout
                android:layout_width="0dp"
                android:layout_weight="1"
                android:layout_height="match_parent">
               <androidx.constraintlayout.widget.ConstraintLayout
                   android:layout_width="0dp"
                   android:layout_height="0dp"
                   android:id="@+id/id_contact_image_choose"
                   app:layout_constraintDimensionRatio="1:1"
                   android:background="@drawable/circular_shape_app_theme"
                   app:layout_constraintTop_toTopOf="parent"
                   app:layout_constraintStart_toStartOf="parent"
                   app:layout_constraintEnd_toEndOf="parent"
                   app:layout_constraintHeight_default="percent"
                   app:layout_constraintHeight_percent="0.7">
                   <ImageView
                       android:layout_width="wrap_content"
                       android:src="@drawable/network_svg_foreground"
                       app:layout_constraintBottom_toBottomOf="parent"
                       android:id="@+id/network"
                       app:layout_constraintTop_toTopOf="parent"
                       app:layout_constraintVertical_bias="0.7"
                       android:layout_marginBottom="@dimen/dimen_4dp"
                       app:layout_constraintStart_toStartOf="parent"
                       app:layout_constraintEnd_toEndOf="parent"
                       android:layout_height="0dp"
                       app:layout_constraintHeight_default="percent"
                       app:layout_constraintHeight_percent="0.3"/>
                   <ImageView
                       android:layout_width="wrap_content"
                       android:id="@+id/plus"
                       app:layout_constraintLeft_toLeftOf="parent"
                       android:layout_marginStart="@dimen/dim_4dp"
                       app:layout_constraintTop_toBottomOf="@+id/money"
                       app:layout_constraintBottom_toTopOf="@+id/network"
                       android:src="@drawable/ic_add_yello_24dp"
                       android:layout_height="0dp"
                       app:layout_constraintHeight_default="percent"
                       app:layout_constraintHeight_percent="0.3"/>
                   <ImageView
                       android:layout_width="@dimen/dim_24dp"
                       android:id="@+id/money"
                       android:layout_marginTop="@dimen/dim_4dp"
                       app:layout_constraintTop_toTopOf="parent"
                       app:layout_constraintStart_toStartOf="parent"
                       app:layout_constraintEnd_toEndOf="parent"
                       android:src="@drawable/money_svg_foreground"
                       android:layout_height="0dp"
                       app:layout_constraintHeight_default="percent"
                       app:layout_constraintHeight_percent="0.3"/>

               </androidx.constraintlayout.widget.ConstraintLayout>
                <TextView
                    android:layout_width="match_parent"
                    android:layout_height="0dp"
                    app:layout_constraintTop_toBottomOf="@+id/id_contact_image_choose"
                    android:text="@string/contacts"
                    android:textSize="@dimen/dimen_10sp"
                    app:layout_constraintStart_toStartOf="parent"
                    app:layout_constraintEnd_toEndOf="parent"
                    android:gravity="center"
                    app:layout_constraintHeight_default="percent"
                    app:layout_constraintHeight_percent="0.25"
                    />

            </androidx.constraintlayout.widget.ConstraintLayout>
            <androidx.constraintlayout.widget.ConstraintLayout
                android:layout_width="0dp"
                android:layout_weight="1"
                android:layout_height="match_parent">
                <androidx.constraintlayout.widget.ConstraintLayout
                    android:layout_width="0dp"
                    android:layout_height="0dp"
                    android:id="@+id/id_contact_image_one"
                    app:layout_constraintDimensionRatio="1:1"
                    android:background="@drawable/circular_shape_gray"
                    app:layout_constraintTop_toTopOf="parent"
                    app:layout_constraintStart_toStartOf="parent"
                    app:layout_constraintEnd_toEndOf="parent"
                    app:layout_constraintHeight_default="percent"
                    app:layout_constraintHeight_percent="0.7">

                </androidx.constraintlayout.widget.ConstraintLayout>
                <TextView
                    android:layout_width="match_parent"
                    android:layout_height="0dp"
                    app:layout_constraintTop_toBottomOf="@+id/id_contact_image_one"
                    android:text="@string/contacts"
                    android:textSize="@dimen/dimen_10sp"
                    android:gravity="center"
                    app:layout_constraintStart_toStartOf="parent"
                    app:layout_constraintEnd_toEndOf="parent"
                    app:layout_constraintHeight_default="percent"
                    app:layout_constraintHeight_percent="0.25"
                    />

            </androidx.constraintlayout.widget.ConstraintLayout>
            <androidx.constraintlayout.widget.ConstraintLayout
                android:layout_width="0dp"
                android:layout_weight="1"
                android:layout_height="match_parent">
                <androidx.constraintlayout.widget.ConstraintLayout
                    android:layout_width="0dp"
                    android:layout_height="0dp"
                    android:id="@+id/id_contact_image_two"
                    app:layout_constraintDimensionRatio="1:1"
                    android:background="@drawable/circular_shape_gray"
                    app:layout_constraintTop_toTopOf="parent"
                    app:layout_constraintStart_toStartOf="parent"
                    app:layout_constraintEnd_toEndOf="parent"
                    app:layout_constraintHeight_default="percent"
                    app:layout_constraintHeight_percent="0.7">

                </androidx.constraintlayout.widget.ConstraintLayout>
                <TextView
                    android:layout_width="match_parent"
                    android:layout_height="0dp"
                    app:layout_constraintTop_toBottomOf="@+id/id_contact_image_two"
                    android:text="@string/contacts"
                    android:gravity="center"
                    android:textSize="@dimen/dimen_10sp"
                    app:layout_constraintHeight_default="percent"
                    app:layout_constraintHeight_percent="0.25"
                    />

            </androidx.constraintlayout.widget.ConstraintLayout>
            <androidx.constraintlayout.widget.ConstraintLayout
                android:layout_width="0dp"
                android:layout_weight="1"
                android:layout_height="match_parent">
                <androidx.constraintlayout.widget.ConstraintLayout
                    android:layout_width="0dp"
                    android:layout_height="0dp"
                    android:id="@+id/id_contact_image_three"
                    app:layout_constraintDimensionRatio="1:1"
                    android:background="@drawable/circular_shape_gray"
                    app:layout_constraintTop_toTopOf="parent"
                    app:layout_constraintStart_toStartOf="parent"
                    app:layout_constraintEnd_toEndOf="parent"
                    app:layout_constraintHeight_default="percent"
                    app:layout_constraintHeight_percent="0.7">

                </androidx.constraintlayout.widget.ConstraintLayout>
                <TextView
                    android:layout_width="match_parent"
                    android:layout_height="0dp"
                    app:layout_constraintTop_toBottomOf="@+id/id_contact_image_three"
                    android:text="@string/contacts"
                    android:textSize="@dimen/dimen_10sp"
                    android:gravity="center"
                    app:layout_constraintHeight_default="percent"
                    app:layout_constraintHeight_percent="0.25"
                    />

            </androidx.constraintlayout.widget.ConstraintLayout>
            <androidx.constraintlayout.widget.ConstraintLayout
                android:layout_width="0dp"
                android:layout_weight="1"
                android:layout_height="match_parent">
                <androidx.constraintlayout.widget.ConstraintLayout
                    android:layout_width="0dp"
                    android:layout_height="0dp"
                    android:id="@+id/id_contact_image_four"
                    app:layout_constraintDimensionRatio="1:1"
                    android:background="@drawable/circular_shape_gray"
                    app:layout_constraintTop_toTopOf="parent"
                    app:layout_constraintStart_toStartOf="parent"
                    app:layout_constraintEnd_toEndOf="parent"
                    app:layout_constraintHeight_default="percent"
                    app:layout_constraintHeight_percent="0.7">

                </androidx.constraintlayout.widget.ConstraintLayout>
                <TextView
                    android:layout_width="match_parent"
                    android:layout_height="0dp"
                    app:layout_constraintTop_toBottomOf="@+id/id_contact_image_four"
                    android:text="@string/contacts"
                    android:textSize="@dimen/dimen_10sp"
                    android:gravity="center"
                    app:layout_constraintHeight_default="percent"
                    app:layout_constraintHeight_percent="0.25"
                    />

            </androidx.constraintlayout.widget.ConstraintLayout>
        </LinearLayout>


        <androidx.viewpager.widget.ViewPager
            android:id="@+id/features"
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:background="@color/white"
            android:layout_marginHorizontal="@dimen/dim_8dp"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintHeight_default="percent"
            app:layout_constraintTop_toBottomOf="@+id/contacts_container"
            app:layout_constraintWidth_percent="0.35" />




</androidx.constraintlayout.widget.ConstraintLayout>
