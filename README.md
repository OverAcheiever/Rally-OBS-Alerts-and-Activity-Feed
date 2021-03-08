# Rally Donation Alerts & Activity Feed 
    ``Donation alerts for streamers who wish to show their viewer's support on stream and an Activity Feed to keep track of donations made through Rally``
# Installation and Getting Started

## Donation Alerts
- Download this repository by clicking [here](https://github.com/OverAcheiever/Rally-OBS-Alerts-and-Activity-Feed/archive/main.zip)
- Extract the zip file to a safe location on your PC. [Installing [WinRar](https://www.win-rar.com/postdownload.html?&L=0) would help with this step if not already installed]
- In OBS, add a new Browser Source by checking the Local file checkbox and then navigating to the location where you extracted the folder and selecting **Activity Feed**. Then click OK.
- Navigate to the location where you extracted the zip file to and find a file named **Settings.json**
- Open the file in a text editor and change the coinSymbol field to your desired coin symbol. For example, a creator with a coin PRO would change the values to look as follows:
	```
	{
	"coinSymbol": "PRO"
	}
	```
## Activity Feed
- In OBS, navigate to **Top Menu → View → Docks → Custom Browser Docks**
- Navigate to extracted folder and right click on **Activity Feed**. Click on properties which opens up a new window. Copy the location from here
- Add a custom dock with a Dock Name of your choice and paste in the copied link in the URL section. 
- On clicking APPLY, a new dock is created.
- Configure the dock to list donations of your coin by clicking the gear icon in the dock and entering your Creator Coin Symbol.
- Under the Activity Feed Settings, click **Test Tip**. Exit settings and Arrange the width of the dock in such a way that the red bar to the right is visible
	``And now you're good to go!``