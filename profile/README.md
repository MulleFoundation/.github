# MulleFoundation

This is the Foundation library written for [mulle-objc](//mulle-objc.github.io).

*MulleFoundation* is collection of libraries to form a complete and powerful Objective-C
class library for *mulle-objc*. As an Objective-C Foundation it contains no graphics code.

The *MulleFoundation* is designed as a plug and play system. Optional library components can be 
left out with no bad side-effect. The concept of the *MulleFoundation* is to avoid actual 
linking into a shared library or executable as much as possible. This has the benefit, that
an optimizing pass can determine, which parts need to be actually linked and which not.

*MulleFoundation* is based on [MulleObjC](//MulleObjC.github.io) and [mulle-core](//mulle-core.github.io).
Some constituent libraries bring in outside dependencies such as *expat* for XML parsing.


## Install

See [foundation-developer](//github.com/MulleFoundation/foundation-developer) for install instructions.


## mulle-sde support

| Library                                                                                | Description
| ---------------------------------------------------------------------------------------|----------------------
| [foundation-developer](//github.com/MulleFoundation/foundation-developer)              | Objective C with mulle-sde and the MulleFoundation
| [mulle-foundation-developer](//github.com/MulleFoundation/mulle-foundation-developer)  | MulleFoundation developer kit for mulle-sde 
