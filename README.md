# -------------> GREATEST OF THREE NUMBERS LOGIC

int largest = num3 > (num1 > num2 ? num1 : num2) ? num3 : ((num1 > num2) ? num1 : num2);

ANSWER -> largest

-------------> FACTORIAL LOGIC

int i,fact=1;  
for(i=1;i<=num1;i++)
{
	fact=fact*i;    
}

ANSWER -> fact 

-------------> LARGEST OF TWO NUMBERS

int largest = (num1 > num2) ? num1 : num2;

ANSWER -> largest

-------------> CELCIUS TO FAHRENHEIT

float fahrenheit= ((num1*9)/5)+3

ANSWER -> fahrenheit

-------------> EVEN OR ODD

String result = num1%2==0 ? "Even" : "Odd";

ANSWER -> result

-------------> ALERT DIALOG


  AlertDialog.Builder myDialog = new AlertDialog.Builder(AlertActivity.this);
                myDialog.setTitle("LOGIN ALERT BOX");
                myDialog.setMessage("MANISH IS A GOOD BOY");
                myDialog.setPositiveButton("OK", new DialogInterface.OnClickListener() {
                    @Override
                    public void onClick(DialogInterface dialogInterface, int i) {
                        dialogInterface.dismiss();
                    }
                });
                myDialog.show();

-------------> LOGIN PASSWORD

                String myEmail = "manishtalreja189@gmail.com";
                String myPassword = "9833137409";
                
                String enteredEmail = edtTxt1.getText().toString();
                String enteredPassword = edtTxt2.getText().toString();
                
                if(enteredEmail.equalsIgnoreCase(myEmail) && enteredPassword.equalsIgnoreCase(myPassword))
                {
                    Toast.makeText(LoginpageActivity.this, "LOGIN SUCCESSFUL", Toast.LENGTH_SHORT).show();
                }
                else
                {
                    Toast.makeText(LoginpageActivity.this, "LOGIN FAILED", Toast.LENGTH_SHORT).show();
                }



onCreate
onStart	
onResume
onPause
onStop
onRestart
onDestroy


Log.d("LifeCycleActivity.java", "ON CREATE METHOD INVOKED");
