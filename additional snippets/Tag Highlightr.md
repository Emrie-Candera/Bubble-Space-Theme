<%*

selection = tp.file.selection();

cursor = tp.file.cursor(0);

const highlightr = await tp.system.suggester(["🍓 Red","🌺 Pink","🍊 Orange","⭐ Gold","🌻 Yellow","🍏 Lime","🍃 Green","🐋 Sky","💧 Blue","🔮 Purple","🏳 White","🐰 Gray","🏴 Black","🎂 Brown",],["red","pink","orange","gold","yellow","lime","green","sky","blue","purple","white","gray","black","brown"]);



if (highlightr === undefined || highlightr === null) {

 return;

} else {

 return "#h/" + highlightr + " ==" + selection + "==";

}

%>
