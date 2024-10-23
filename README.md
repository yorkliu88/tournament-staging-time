# tournament-staging-time
https://yorkliu88.github.io/tournament-staging-time/staging-time.html

If the current time pass the staging time then red. Curent time is within 30min before staging time then black. Current time is more than 30min before staging time then green.
Comparison ignore the date, only time of the day

Auto refresh set to long for now

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
