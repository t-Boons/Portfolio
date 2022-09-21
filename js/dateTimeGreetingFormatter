
function setGreetingFromTime(elementToWriteTo)
{
    const d = new Date();
    var hours = d.getHours();

    var text;
    if(isValueBetween(hours, 0, 6))
    {
        text = "Good night,";
    }
    if(isValueBetween(hours, 6, 12))
    {
        text = "Good morning,";
    }
    if(isValueBetween(hours, 12, 18))
    {
        text = "Good afternoon,";
    }
    if(isValueBetween(hours, 18, 24))
    {
        text = "Good evening,";
    }

    elementToWriteTo.innerHTML = text;
}

function isValueBetween(v, min, max)
{
    return v >= min && v < max;
}