# ShadowButton-Example

# Preview
![alt text](https://firebasestorage.googleapis.com/v0/b/fir-7f4d3.appspot.com/o/Screenshot_1569570787.png?alt=media&token=6cc44c0c-7ebb-4838-a255-3a930edba669)

# Integration


    allprojects {
      repositories {
        ...
        maven { url 'https://jitpack.io' }
      }
     }
     
     
    dependencies {
        implementation 'com.github.Sanjaymaliya:ShadowButton:1.1'
    }

# 
# Uses
  
      This library use to set custom shedow for the button view
      
       <com.android.sbm.ShadowButton
        android:id="@+id/Button1"
        android:layout_width="250dp"
        android:layout_height="wrap_content"
        android:padding="30dp"
        app:buttonColor="@color/colorLightPink"
        app:shadowColor="@color/shadow_color"
        app:cornerRadius="0dp"
        app:onUpShadowSize="10dp"
        app:pressedShadowSize="10dp"
        android:text="Rectangle  Button"
        android:textColor="@android:color/white"/>
        
        
  # Attributes
  
      button color :  app:buttonColor="@color/colorLightPink"
      shadow color :  app:shadowColor="@color/shadow_color"
      cornerRadius :  app:cornerRadius="0dp"
      ShadowSize   :  app:onUpShadowSize="10dp"
      ShadowSize   :  app:pressedShadowSize="10dp"
      
