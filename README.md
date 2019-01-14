# BR_Test
Broadcast Reaceiver demo App

1) Create class as a child of BroadcatReceiver 
2) it abstract class having an abstract method onReceive()
3) Configure the events by using EtentFilter
       IntentFilter i= new IntentFilter()
          i.e. addAction(Intent.action_name)  i.e. ACTION_HEADSET_PLUG
