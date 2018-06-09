# Summary for the 64th meeting of Ecma TC39

Ecma Technical Committee 39 held three day meeting at Bloomberg in NYC on May 22nd - May 24th, 2018. [Agenda can be found here](https://github.com/tc39/agendas/blob/master/2018/05.md) (note: committee has adopted new agenda formart based on the stage of proposals)

## New Proposals
TC39 discussed 10 new proposals. 7 entered staging process to discuss towards specification, and 3 remains at Stage 0 for further investigation before consensus.  

### Advanced to Stage 1 
- [Sequence properties in Unicode property escapes](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#11ia-sequence-properties-in-unicode-property-escapes)
- [Module Keys](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-23.md#module-keys-strawman-for-stage-1)
- [Class Static Block](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-23.md#class-static-block)
- [Class Access Expressions](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-23.md#class-access-expressions)
- [Pattern Matching](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-24.md#pattern-matching-for-stage-1)
- [RegExp Match array offsets](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-24.md#bl%C3%B6cks-syntax-for-stage-0)

### Advanced to Stage 2 
- [Well-formed JSON.stringify](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#stringprototypecodepoints-for-stage-2)

### Needs more discussion (remains Stage 0) 
- [Tagged Collection Literals](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-24.md#tagged-collection-literals-for-stage-1)
- [Symbol.thenable](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-24.md#symbolthenable-for-stage-1-or-2)
- ["Blöcks" syntax](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-24.md#bl%C3%B6cks-syntax-for-stage-0)

## Existing Proposals

### Advanced to Stage 2
- [Object.fromEntries](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#objectfromentries-to-stage-2)
- [Set Methods](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#set-methods)
- [Realms](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-23.md#realms)
- [Function.prototype.toString() censorship](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#functionprototypetostring-censorship-for-stage-2). Please also reffer to [continued discussion](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-24.md#functionprototypetostring-censorship-for-stage-2-continued-discussion)
- [Top Level Await](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#top-level-await)
### Advanced to Stage 3
- [Symbol.prototype.description](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#symbolprototypedescription-for-stage-3)
- [Static class features](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-23.md#static-class-features-for-stage-3)
### Advanced to Stage 4  (will be added to ES2019)
- [Optional catch binding - Michael Ficarra](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#11id-optional-catch-binding-for-stage-4)
- [ECMAScript as a superset of JSON](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#11ie-ecmascript-as-a-superset-of-json)
### Demoted to Stage 2
A conflict with other proposal was found, champion group and committee has decided to move following proposal from Stage 3 to Sage 2. Please see notes for more information.
- [Numeric separators](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-24.md#numeric-separators-update).

### Needs more discussion/information
These proposals were discussed but did not advance to next stage at the meeting. Please refer to "Conclusion / Resolution" section on the notes to see the outcome of discussion.
- [Binary AST](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-24.md#binary-ast)
- [Function.prototype.toString revision](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#functionprototypetostring-revision-updates-slides-and-stage-4)
- [String.prototype.codePoints](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#stringprototypecodepoints-for-stage-2)
- [Class fields](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-23.md#class-fields-status-update)

### Updates
Status updates from proposals working twards stage advancement.
- [Intl Updates](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#intl-updates)
- [Decorators](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-23.md#decorators-towards-stage-3-additional-notes)
- [Array.prototype.flatten rename to flat](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#arrayprototypeflatten-rename)
- [Big Int](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#bigint-status-update)
- [String.prototype.matchAll](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#revisiting-stringprototypematchall)

## Changes to existing specification

### Consensus Reached Pull Requests 
- [Normative: Cleanup Time Values and Time Range](https://github.com/tc39/ecma262/pull/1144)
- [Normative: Add export * as ns from "mod” to Export production and Module Semantics](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#9ib-normative-add-export--as-ns-from-mod-to-export-production-and-module-semantics)
- [SuperProperty evaluation order](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-24.md#superproperty-evaluation-order)

### Needs more discussion
- [Rename Atomics.wake](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#rename-atomicswake)
- [Updates and a question to resolve on String.prototype.matchAll](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#updates-and-a-question-to-resolve-on-stringprototypematchall)

## General Discussions 
Topics related to ECMAScript specification activities. 
- [Supporting other languages in ES module graphs](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-23.md#supporting-other-languages-in-es-module-graphs-updates)
- [Stopping exfiltration: Massive privacy violations vs boundaries](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-23.md#stopping-exfiltration-massive-privacy-violations-vs-boundaries)

## Organizational update
- [~400 new tests added to Test262](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#test262) from various contributors.
- [CoC commmittee updates](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#8-updates-from-the-coc-committee)
- [Update to the How We Work Documentation project and Website](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#11if-update-to-the-how-we-work-documentation-project-and-website)
- [2019 / 2020 meeting scheduling](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-22.md#11ic-20192020-meeting-scheduling-update)
- [TC53 - variables which are based on ECMAScript](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-24.md#further-secretariat-updates)
- [Editor group update](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-23.md#expanding-group-of-editors)
- [ECMAScript PDF is most downloaded spec in ECMA](https://github.com/rwaldron/tc39-notes/blob/master/es9/2018-05/may-23.md#ecma-secretariat-update)
