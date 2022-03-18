# Create-back-to-top-button-in-website
Create back to top button in website
$(function() {
    $("#top").on('click', function() {
        var position = $("#image").offset().top;
        $("HTML, BODY").animate({
            scrollTop: position
        }, 1000);
    });
});
