 var myClock = document.getElementsByClassName('clock');
        var sHors = "06";
        var sMins = "09";
        var sSecs = 60;
        var getSecs = function () {
            sSecs--;
            if (sSecs < 0) {
                sSecs = 59;
                sMins--;
                if (sMins <= 9)
                    sMins = "0" + sMins;
            }
            if (sMins == "0-1") {
                sMins = 5;
                sHors--;
                if (sHors <= 9)
                    sHors = "0" + sHors;
            }
            if (sSecs <= 9)
                sSecs = "0" + sSecs;
            for (var i = 0; i < myClock.length; i++) {
                if (sHors == "0-1") {
                    sHors = "00";
                    sMins = "00";
                    sSecs = "00";
                    myClock[i].innerHTML = "<span>" + sHors + "</span>" + "<b> : </b>" + "<span>" + sMins +
                        "</span>" + "<b> : </b>" + "<span>" + sSecs + "</span>";
                } else {
                    myClock[i].innerHTML = "<span>" + sHors + "</span>" + "<b> : </b>" + "<span>" + sMins +
                        "</span>" + "<b> : </b>" + "<span>" + sSecs + "</span>";
                }
            }
            setTimeout('getSecs()', 1000);
        }
        //-->