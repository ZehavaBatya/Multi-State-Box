// For future purposes too

$w.onReady(function () {

    const blackColor = "#000000"; 
    const whiteColor = "#FFFFFF"; 
    

    $w('#firstButton').onClick(() => {
        $w('#stateBox').changeState("firstState");
    });

    $w('#secondButton').onClick(() => {
        $w('#stateBox').changeState("secondState");
    });

    $w('#thirdButton').onClick(() => {
        $w('#stateBox').changeState("thirdState");
    });

    $w('#fourthButton').onClick(() => {
        $w('#stateBox').changeState("fourthState");
    });


    $w("#stateBox").onChange((event) => {

        const buttonNames = ["first", "second", "third", "fourth"];

        buttonNames.forEach(buttonName => {
            let button = $w("#" + buttonName + "Button"); 
            let state = buttonName + "State"; 

            if (event.target.currentState.id === state) {
                button.style.backgroundColor = blackColor; 
            } else {
                button.style.backgroundColor = whiteColor; 
            }
        });
    });
});
