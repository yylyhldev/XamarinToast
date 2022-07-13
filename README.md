# Toast Plugin for Android, iOS  and Windows Phone
It's compatible with portable projects as well as .Net standard projects.

To display Toast PopUp Write in PCL project classes or code behind  this line of code: 

CrossToastPopUp.Current.ShowToastMessage("Message");
With Plugin.Toast 2.1.1  You can create your custom Toasts  now!! enjoy!!

Create your #Custom #Toasts, with custom Colors and durations

Let me know about your feedback and any suggestion to ameliorate the plugin.
#Xamarin #Forms #Toast #Plugin

Thank you in advance for any contribution.

: ![alt-text](https://github.com/ishrakland/Toast/blob/master/IMG/Toast2.1.1.gif)


Fork Tip:<br/>
1.only need copy ShowToastPopUp.cs and IToastPopUp.cs；<br/>
2.Xamarin.Forms.DependencyService.Register<ShowToastPopUp>();；<br/>
3.public IToastPopUp Toast => DependencyService.Get<IToastPopUp>();；<br/>
4.Toast.ToastMessage("message");
