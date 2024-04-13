# class1
# Unit convert App

# Hope this will help beginner Android Developer.
In this App I have make a simple function of [onClick_function] on the submit button which takes the input from the user in the [edit_Text] and covert to the kg unit to pound unit. 



## Color Reference

| HEX Color |

| Color name :Black | ![#000000]

| Color name :Studio | ![#6750A3]

| Color name :White | ![#ffffff]

| ------------------------------------------------------------------ |


# What I learnt in this project:
[
     (1.) [Toast] function.
     (2.) [findViewById(R.id.)] function.
     (3.) button.setOnClickListener(new View.OnClickListener()) {
            @Override
            public void onClick(View v) {
                Toast.makeText(MainActivity.this, "Hey this Toast function", Toast.LENGTH_SHORT).show();
                String s =editText.getText().toString();
                int kg = Integer.parseInt(s);
                double pound = 2.205*kg;
                textView3.setText("The corresponing value in pound is "+ pound);
            }}

]
## Screenshots


 ![Screenshot of Running App](<Screenshot 2024-04-13 120638.png>)

 ## MENTOR
 CODE WITH HARRY
