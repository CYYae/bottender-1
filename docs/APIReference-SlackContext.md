<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

## platform

The name of the platform.

Returns **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** 

## event

The event instance.

Returns **SlackEvent** 

## session

The session state of the context.

Returns **SlackSession?** 

## sendText

Send text to the owner of then session.

**Parameters**

-   `text` **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** 

Returns **[Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)&lt;any>** 

## rawEvent

Underlying raw event from Slack.

Returns **SlackRawEvent** 

## isMessage

Determine if the event is a message event.

Returns **[boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)** 

## isChannelsMessage

Determine if the event is a message event sent from channels.

Returns **[boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)** 

## isGroupsMessage

Determine if the event is a message event sent from groups.

Returns **[boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)** 

## isImMessage

Determine if the event is a message event sent from instant messaging.

Returns **[boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)** 

## isMpimMessage

Determine if the event is a message event sent from multiple people instant messaging.

Returns **[boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)** 

## message

The message object from Slack raw event.

Returns **Message?** 

## isTextMessage

Determine if the event is a message event which includes text.

Returns **[boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)** 