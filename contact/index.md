---
layout: page
title: גם אתם בשוק?
excerpt: אם אתם בשוק, צרו קשר וניהיה בשוק ביחד
comments: false
---
מוצאים את עצמכם בשוק מדברים שקוראים או שקראתם עליהם בארץ? רוצים שאתייחס לנושא?
שילחו לי לינק לכתבה ואולי גם אני אהיה בשוק...

<form name="sentMessage" id="contactForm">
    <div class="row control-group">
        <div class="col-md-6">
            <div class="form-group">
                <input type="text" class="form-control" placeholder="שם *" id="name" name="name" required data-validation-required-message="נא להזין שם.">
                <p class="help-block text-danger"></p>
            </div>
            <div class="form-group">
                <input type="email" class="form-control" placeholder="אימייל *" id="email" name="email" required data-validation-required-message="נא להזין כתובת אימייל.">
                <p class="help-block text-danger"></p>
            </div>
            <div class="form-group">
                <input type="url" class="form-control" placeholder="לינק לכתבה *" id="website" name="website" required
                       data-validation-regex-regex="(http[s]?:\/\/){0,1}(www\.){0,1}[a-zA-Z0-9\.\-]+\.[a-zA-Z]{2,5}[\.]{0,1}"
                       data-validation-regex-message="נא להזין כתובת תקינה לכבתה" />
                <p class="help-block text-danger"></p>
            </div>
        </div>
        <div class="col-md-6">
            <div class="form-group">
                <textarea class="form-control" placeholder="הודעה *" id="message" name="message" required data-validation-required-message="נא לכתוב הודעה."></textarea>
                <p class="help-block text-danger"></p>
            </div>
        </div>
    </div>
    <div id="success"></div>
    <div class="row control-group">
        <div class="col-lg-12 text-center">
            <button type="submit" class="btn btn-xl">שלח</button>
        </div>
    </div>
    <input type="hidden" name="_cc" value="mtk@lighthost.co.il" />
    <input type="text" name="_gotcha" style="display:none" />
    <input type="hidden" name="_subject" value="שוקה, גם אני בשוק!" />
</form>

<!-- / contact form -->