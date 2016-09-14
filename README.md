Redmine Glip WebHook Plugin
======================

UNDER CONSTRUCTION !
DO not USE !!

A Redmine plugin to posts to glip webhook.

Author
------------------------------
* @airmoi
* based on @suer redmine_webhook

Install
------------------------------
Type below commands:

    $ cd $RAILS_ROOT/plugins
    $ git clone git://github.com/airmoi/redmine_glip_webhook.git
    $ rake redmine:plugins:migrate RAILS_ENV=production

Then, restart your redmine.

Post Data Example
------------------------------

### Issue opened
TODO
   

### Issue updated
TODO

Requirements
------------------------------
* Redmine 2.4, 2.6, 3.0


Known Limitations
------------------------------

An update from context menu doesn't call a webhook event.
It is caused by a lack of functionality hooking in Redmine.
Please see https://github.com/suer/redmine_webhook/issues/4 for details.

This limitation has been affected on all Redmine versions includes 2.4, 2.6,
and 3.0. It is not fixed in end of April, 2015.


License
------------------------------
The MIT License (MIT)
Copyright (c) airmoi

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
