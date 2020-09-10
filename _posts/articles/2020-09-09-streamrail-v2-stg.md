---
layout: post
title: "streamrail-v2-stg"
excerpt: "streamrail-v2-stg"
categories: articles
tags: [sample-post, streamrail]
comments: false
share: false
---
<script type="text/javascript">
      (function() {
        var gdprAppliesGlobally = false;

        function addFrame() {
          if (!window.frames['__cmpLocator']) {
            if (document.body) {
              var body = document.body,
                iframe = document.createElement('iframe');

              iframe.style = 'display:none';

              iframe.name = '__cmpLocator';

              body.appendChild(iframe);
            } else {
              // In the case where this stub is located in the head,

              // this allows us to inject the iframe more quickly than

              // relying on DOMContentLoaded or other events.

              setTimeout(addFrame, 5);
            }
          }
        }

        addFrame();

        function stubCMP() {
          var b = arguments;

          __cmp.a = __cmp.a || [];

          if (!b.length) return __cmp.a;
          else if (b[0] === 'ping') {
            b[2](
              {
                gdprAppliesGlobally: gdprAppliesGlobally,

                cmpLoaded: false,
              },
              true,
            );
          } else if (b[0] === 'getVendorConsents') {
            setTimeout(
              () =>
                b[2](
                  {
                    metadata: 'BOJObISOJObISAABAAENAA4AAAAAoAAA',
                    gdprApplies: 'true',
                    hasGlobalScope: 'true',
                    purposeConsents: { '2': true, '4': true },
                    vendorConsents: { '354': true },
                  },
                  true,
                ),
              200,
            );
          } else if (b[0] === 'getConsentData') {
            setTimeout(
              () =>
                b[2](
                  {
                    consentData: 'BOJObISOJObISAABAAENAA4AAAAAoAAA___asdfasdfasDF__asdfasdf',
                  },
                  true,
                ),
              300,
            );
          } else {
            __cmp.a.push([].slice.apply(b));
          }
        }

        function cmpMsgHandler(event) {
          try {
            var msgIsString = typeof event.data === 'string';

            var json = msgIsString ? JSON.parse(event.data) : event.data;

            if (json.__cmpCall) {
              var i = json.__cmpCall;

              window.__cmp(i.command, i.parameter, function(retValue, success) {
                var returnMsg = {
                  __cmpReturn: {
                    returnValue: retValue,

                    success: success,

                    callId: i.callId,
                  },
                };

                event.source.postMessage(msgIsString ? JSON.stringify(returnMsg) : returnMsg, '*');
              });
            }
          } catch (e) {}
        }

        if (typeof __cmp !== 'function') {
          window.__cmp = stubCMP;

          __cmp.msgHandler = cmpMsgHandler;

          if (window.addEventListener) window.addEventListener('message', cmpMsgHandler, false);
          else window.attachEvent('onmessage', cmpMsgHandler);
        }
      })();
    </script>


Story: 

<div class="apester-media" data-media-id="5f591d9a5d97db7bb558d736" height="512"></div>

<script async src="https://static.stg.apester.com/js/sdk/latest/apester-sdk.js"></script>
