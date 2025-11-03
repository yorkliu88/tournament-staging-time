# tournament-staging-time
https://yorkliu88.github.io/tournament-staging-time/staging-time.html

Color Logic:
Red if the current time is after the staging time.
Black if the current time is on or before the staging time.

Comparison ignore the date, only time of the day

Auto refresh set to long for now

In GitHub Setting Danger Zone make the project private. After making public, in the Setting Page need to make Root path visable

In the Google API, delete the website restriction http://www.risingstarsinfinite.com, or make it no restrictions

      var spreadsheetId = '1PHXNh74wemifZlv91l9hOZ-1-WTtrcp7gI8_-JR872c';  // Your Google Sheet ID
      var automallTime = 'Sheet1!B1';  // Specify the range (e.g., A1)
      var missionTime = 'Sheet1!B2';  // Specify the range (e.g., A1)
      var apiKey = 'AIzaSyAwq2XmrASVwh8Eq6D7LAgunSBAST6Gup4';          // Replace with your Google API Key

      // URLs to fetch staging times for AutoMall (A1) and Mission (B1)
      var urlAutoMall = `https://sheets.googleapis.com/v4/spreadsheets/${spreadsheetId}/values/${automallTime}?key=${apiKey}`;
      var urlMission = `https://sheets.googleapis.com/v4/spreadsheets/${spreadsheetId}/values/${missionTime}?key=${apiKey}`;


= Embeded Twich in Google Site Original =
<div style="text-align: center;">
    <iframe src="https://player.twitch.tv/?channel=rinsingstars&parent=sites.google.com&parent=play.google.com"
            height="1920"
            width="100%"
            frameborder="0"
            scrolling="no"
            allowfullscreen="true">
    </iframe>
</div>

= Match Schedule Update (host in Github) will load the tournament software match export xlsx and convert to google sheet staging-time-match-schedule-update and exeucte a App Script to populate that sheet. A public accessable Staging-Time-and-Player will access to the Match Time schedule and the Staging Time to show the players

= When run into the Github doesn't write into Google Sheet. Usually it is Cor issue, debug that, use broswer to run the GitHub hosted page and show error console to ChatGPT =
