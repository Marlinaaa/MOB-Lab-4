# MOB-Lab-4
# 4.1
1.	 How do you add images to an Android Studio project? Choose one: 
**->Copy the image files into your project's drawable folder.**
2.	How do you make an ImageView clickable like a simple Button? Choose one:
**-> Add the android:onClick attribute to the ImageView in the layout and use it to call the click handler in the Activity.
3.	Which rule applies to a click handler called from the attribute in the layout? Choose one:
**->The click handler must customize the View.OnClickListener class and override its click handler to perform some action.
# 4.2
1.	What's the most important difference between checkboxes and a RadioGroup of radio buttons? Choose one: 
**->The major difference is that checkboxes enable multiple selections, while a RadioGroup allows only one selection.
2.	Which layout group lets you align a set of CheckBox elements vertically? Choose one: 
**-> LinearLayout
3.	Which of the following is the method of the Checkable interface to check the state of a radio button (that is, whether it has been selected or not)? 
**-> isChecked()
# 4.3
1.	What is the name of the file in which you create options menu items? Choose one:
**->menu_main.xml
2.	Which method is called when an options menu item is clicked? Choose one:
**->onOptionsItemSelected(MenuItem item)
3.	Which of the following statements sets the title for an alert dialog? Choose one:
**->myAlertBuilder.setTitle("Alert");
4.	Where do you create a DialogFragment for a date picker? Choose one:
**->In the onCreateView() method in the extension of DialogFragment.
# 4.4
1.	Which template provides an Activity with an options menu and the v7 appcompat support library Toolbar as the app bar? Choose one: 
**->Basic Activity template
2.	Which dependency do you need in order to use a TabLayout? Choose one:
**->com.android.support:design
3.	Where do you define each child Activity and parent Activity to provide Up navigation? Choose one: 
**->To provide the Up button for a child screen Activity, declare the parent Activity in the child Activity section of the activity_main.xml file.
# 4.5
1.	Which of the following statements about a RecyclerView is false? Choose one:
**-> You don't need a layout manager with a RecyclerView to handle the hierarchy and layout of View elements.
2.	Which of the following is the primary component you need to provide to an adapter a View item and its position within a RecyclerView? Choose one:
**->RecyclerView.ViewHolder
3.	Which interface do you need to implement in order to listen and respond to user clicks in a RecyclerView? Choose one:
**->RecyclerView.Adapter

