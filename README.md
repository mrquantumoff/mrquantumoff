![langs]($.ajax({
  type: 'GET',
  url: 'https://wakatime.com/share/@0d89d581-d4f6-44ab-8ad2-18581c59286b/65b58e46-9dc1-405f-8383-fafc6ba7ff3a.json',
  dataType: 'jsonp',
  success: function(response) {
    console.log(response.data);
  },
});)
