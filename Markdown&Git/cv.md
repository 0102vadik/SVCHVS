#Milko Vadim

![My photo](http://cdn.bru.by/cache/student/council/2022/img_1_1.jpg)

## Short information

---
I am a 3rd course student of the Belarusian-Russian University.
I like programming, at the moment I want to develop as 
a backend developer in php. I am in a team with my classmates
and already in the third year we are working as a team in the
company GAZSTROYPROM.

##Skills

---
I studied such programming languages as `C++`,
`Java`, `C#`,` PHP`, `HTML`, `CSS`, `JavaScript`. 
Lately I've been 
using a `PHP` framework like `Laravel`. In my work I use 
such programs as `PhpStorm`, `OpenServer`, `VisualStudioCode`,
`GitHub`. In addition to these programs, I can work with
`VisualStudio`, `CodeBlock`, `MS SQL Server`, `IntelliJ IDEA`.

##Сode example

---
``` Java
function ajaxChart(dateStart,dateEnd) {
    var dfr = $.Deferred();
    $.ajax({
        url: "/ajaxAnalyticsChartsMachines",
        type: 'get',
        headers: {
        'X-CSRF-TOKEN': $('meta[name="csrf-token"]').attr('content')
       },
    data: {
        vin: document.getElementById('VIN').innerHTML,
        dateStart: dateStart, //document.getElementById('start-date').value,
        dateEnd: dateEnd//document.getElementById('end-date').value
    }, success: function (arrayDynamics) {
        dfr.resolve({arrayDynamics: arrayDynamics});
        }
    })
return dfr;
}
```

##Work experience

---
As part of the team, I completed the project of an information and analytical system,
which we presented at the international Case-in competition and won first place. 
The Laravel 8.0 framework was used to implement the project. 
[Project link](http://case-in-bru.hostingem.ru/indexTask14.php).