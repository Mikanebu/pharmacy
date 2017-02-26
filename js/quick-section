$(document).ready(function() {
	$('#right-button').click(function() {
		var marginCurrent = $('.quick-section').css("margin-left");
		if (marginCurrent == "-1513px") {
			marginCurrent = "0px";
			$('.quick-section').css("margin-left", "0px");
		} else if (marginCurrent == "-1815px") {
			marginCurrent = "-302px";
			$('.quick-section').css("margin-left", "-302px");
		}
		switch (marginCurrent) {
			case "0px":
				marginTarget = "-605px";
				break;
			case "-302px":
				marginTarget = "-907px";
				break;
			case "-605px":
				marginTarget = "-1210px";
				break;
			case "-907px":
				marginTarget = "-1513px";
				break;
			case "-1210px":
				marginTarget = "-1815px";
				break;
			default:
				return false;
				break;
		}
		$('.quick-section').animate({
			marginLeft: marginTarget
		}, "200");
		return false;
	});

	$('#left-button').click(function() {
		var marginCurrent = $('.quick-section').css("margin-left");
		if (marginCurrent == "0px") {
			marginCurrent = "-1513px";
			$('.quick-section').css("margin-left", "-1513px");
		} else if (marginCurrent == "-302px") {
			marginCurrent = "-1815px";
			$('.quick-section').css("margin-left", "-1815px");
		}
		switch (marginCurrent) {
			case "-1815px":
				marginTarget = "-1210px";
				break;
			case "-1513px":
				marginTarget = "-907px";
				break;
			case "-1210px":
				marginTarget = "-605px";
				break;
			case "-907px":
				marginTarget = "-302px";
				break;
			case "-605px":
				marginTarget = "0px";
				break;
			default:
				return false;
				break;
		}
		$('.quick-section').animate({
			marginLeft: marginTarget
		}, "200");
		return false;
	});
});
