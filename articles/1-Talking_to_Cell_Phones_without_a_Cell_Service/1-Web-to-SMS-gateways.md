Web-to-SMS Gateways
===================

Web-to-SMS gateways are web sites which are dedicated to allowing you to send or
recieve messages to and/or from devices which use SMS as their primary form of
textual communication, such as Cell Phones. While many of them require you to
pay money to use them, a few can be used for free, and some don't require much
information about you to use. While they do offer some privacy advantages from
the ability to register new accounts without volunteering the intrusive amount
of information required by other ways of talking to cell phones, but **Hands**
**down, the primary advantage of Web-to-SMS gateways for phoneless people is**
**EASE OF USE when contacting people who only use phones.** They do not offer
any particularly tenable improvements to privacy in the long term, but they make
it super easy for people who choose not to use cell phones to interact with
those who do. The services listed on this page are all Free of Cost, but none of
them are Free as in Freedom.

[Google Voice](https://voice.google.com)
----------------------------------------

Far and away the hardest to get, requiring the most information and only
available to people who can use a US phone number already, but also the most
flexible and best supported, Google Voice is pretty much a one-stop-shop for
Web-to-Phone services. Google Account holders who wish to sign up for a Google
Voice account will need to use an existing phone number capable of recieving SMS
messages to confirm your eligibility for an account.

With Google Voice, you'll be able to send and recieve text messages from a
normal-looking phone number, which will remain your phone number for as long
as you have your Google Voice account.

With the addition of a tablet or a deactivated/repurposed smartphone, you can
install the Google Voice app, which will also allow you to make phone calls to
and from the number using only Wi-Fi, and without requiring a data plan. This
feature isn't shared by any other Web-to-SMS gateway I know of.

###Requirements to Sign Up

  * A Google Account
    - An existing e-mail address
    - A normal, SMS capable phone(Temporarily)
    - Name or Psuedonym
    - Pass a Captcha(Requiring Javascript)
  * A normal, SMS capable phone(Temporarily)

###Pro's(FEATURES!)

  * Extremely easy to use(Once you manage to sign up).
  * Uses proper TLS
  * Gives you a fixed, long-term phone number for other people to text.
  * Least obnoxious user-interface of any of the options.
  * Voicemail! People who call you can leave voice mail messages

###Con's(Basically, Google.)

  * Very difficult to sign up for an account. Requires an account with Google,
  which requires at various times for you to have the ability to recieve SMS
  already, which sort of defeats the purpose. Borrow a cell phone when you sign
  up.
  * You have a long-term account tied to a long-term phone number corresponding
  to you, and it's very difficult to sign up for a new account. Per every single
  reasonable person's expectations, GOOGLE KNOWS WHO YOU ARE.
  * Voicemail Transcription! Google uses your voicemail for practice teaching
  machines to recognize spoken words and turning them into text. Sometimes
  poorly, but more importantly, it means that Google is also listening to your
  voicemail.
  * General Google intrusiveness.

[TextNow](https://www.textnow.com)
----------------------------------

Balancing some of the features of both Google Voice and TextPort is TextNow.
Textnow requires less information than Google Voice, and it works without an
account from another service. They operate phone services and phone services
only, and your account is only used for your phone services.

With TextNow, sending and recieving text messages is possible for anyone who can
complete a captcha. It does not include Voicemail yet, but it appears that
Voicemail and Calling are planned features.

All in all, I'd say TextNow is the best all-around option for people cutting the
phone cord.

###Requirements to Sign Up

  * An e-mail address
  * Name or Pseudonym
  * Pass a Captcha(Requiring Javascript)

###Pro's

  * Pretty easy to sign up for.
  * Uses proper TLS
  * Gives you a semi long-term phone number for other people to text.
  * Familiar, reasonably rich user interface.

###Con's

  * Not a whole lot. It's pretty javascript heavy, but an ad-blocking hosts
  file, a well-configured NoScript policy, or just using the Tor browser improve
  client-side performance considerably.

[TextPort](http://www.textport.com)
-----------------------------------

Much much easier to get, but much less flexible and carrying some various
security issues, TextPort is another worthwhile option for sending SMS messages
from the Web. TextPort is much less refined-looking compared to the other
options. It's included on this list because it doesn't require an account in
order to send outgoing messages.

It has fewer features than any of the others, and it also has issues with TLS
that make it unsuitable in terms of security. That said, it's easy to use,
doesn't require an account for outgoing, doesn't require activation should you
choose to use an account to recieve incoming messages.

###Requirements to Sign Up

  * Strictly speaking, signup is not required for sending outgoing messages.
  * An e-mail address
  * Name or Pseudonym
  * Pass a Captcha(No javascript requirement)

###Pro's

  * Signup not required for Outgoing Messages
  * Easiest signup
  * No javascript required
  * No long-term number, instead it uses aliases for numbers that cycle
  eventually.

###Con's

  * Doesn't properly use TLS. Go to Let's Encrypt guys. Get it together.
  * Least nice interface.
  * No long-term number, instead it uses aliases for numbers that cycle
  eventually.

####Shortcomings of Web-to-SMS Gateways

  * Lack of Signal/Axolotl Integration: While, with Google Voice, you can indeed
  use the Signal protocol, with most of these Web-to-SMS gateways, you can't use
  the wonderful [Signal](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms&hl=en)
  messaging system available to regular phone users.
  * Lack of iMessage Integration: Same as above, except the iMessage protocol is
  also more-or-less impossible for non-iDevices to talk to until Apple lets
  others talk to their devices. Install [Signal](https://itunes.apple.com/us/app/signal-private-messenger/id874139669?mt=8)
  iUsers, the rest of the world will thank you.
  * Single Point of Failure: Much like traditional cell phone companies, and in
  some ways, worse, the Web-to-SMS gateway becomes a centralized point of
  failure, in that if it fails, bans your account, or you are kept from
  connecting by anything else, something you're dependent on for messaging
  also fails. Centralized organizations all share this weakness and can't really
  be expected to be reliable, whether thay are phone companies or traditional
  web services.
