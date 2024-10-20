# tournament-staging-time
https://yorkliu88.github.io/tournament-staging-time/staging-time.html

      var spreadsheetId = '1PHXNh74wemifZlv91l9hOZ-1-WTtrcp7gI8_-JR872c';  // Your Google Sheet ID
      var automallTime = 'Sheet1!B1';  // Specify the range (e.g., A1)
      var missionTime = 'Sheet1!B2';  // Specify the range (e.g., A1)
      var apiKey = 'AIzaSyAwq2XmrASVwh8Eq6D7LAgunSBAST6Gup4';          // Replace with your Google API Key

      // URLs to fetch staging times for AutoMall (A1) and Mission (B1)
      var urlAutoMall = `https://sheets.googleapis.com/v4/spreadsheets/${spreadsheetId}/values/${automallTime}?key=${apiKey}`;
      var urlMission = `https://sheets.googleapis.com/v4/spreadsheets/${spreadsheetId}/values/${missionTime}?key=${apiKey}`;
