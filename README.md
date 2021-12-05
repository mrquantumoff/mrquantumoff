$.ajax({
  type: 'GET',
  url: 'https://wakatime.com/share/@0d89d581-d4f6-44ab-8ad2-18581c59286b/5a7a3080-5ddd-4f60-ad79-69ea6573d78d.json',
  dataType: 'jsonp',
  success: function(response) {
    console.log(response.data);
  },
});
