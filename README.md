# README
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
Header 4

This is an unordered list following a header.
This is an unordered list following a header.
This is an unordered list following a header.
HEADER 5
This is an ordered list following a header.
This is an ordered list following a header.
This is an ordered list following a header.
HEADER 6
head1	head two	three
ok	good swedish fish	nice
out of stock	good and plenty	nice
ok	good oreos	hmm
ok	good zoute drop	yumm
There’s a horizontal rule below this.

Here is an unordered list:

Item foo
Item bar
Item baz
Item zip
And an ordered list:

Item one
Item two
Item three
Item four
And a nested list:

level 1 item
level 2 item
level 2 item
level 3 item
level 3 item
level 1 item
level 2 item
level 2 item
level 2 item
level 1 item
level 2 item
level 2 item
level 1 item
Small image

Octocat

Large image

Branching

Definition lists can be used with HTML syntax.

Name
Godzilla
Born
1952
Birthplace
Japan
Color
Green
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
The final element.

// (c) Facebook, Inc. and its affiliates. Confidential and proprietary.

/***
 * This is a bridge file for Audience Network Unity SDK.
 *
 * This file may be used to build your own Audience Network iOS SDK wrapper,
 * but note that we don't support customisations of the Audience Network codebase.
 *
 ***/

#import <UIKit/UIKit.h>

#import <FBAudienceNetwork/FBAdBridgeContainer.h>
#import <FBAudienceNetwork/FBAdDefines.h>

FB_EXTERN_C_BEGIN

// External to this project
typedef NS_ENUM(NSInteger, FBGLViewController) {
    FBGLViewControllerNone,
    FBGLViewControllerUnity,
    FBGLViewControllerCocos2D,
};

__attribute__((weak)) extern UIViewController *UnityGetGLViewController(void);
__attribute__((__always_inline__)) extern FBGLViewController fbad_Cocos2DGetGLViewController(
    UIViewController **glViewController);

__attribute__((__always_inline__)) extern UIViewController *fbad_GetGLViewController(void);
__attribute__((__always_inline__)) extern FBGLViewController fbad_UnityGetGLViewController(
    UIViewController **glViewController);

FB_EXTERN_C_END
