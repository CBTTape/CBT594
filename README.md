# CBT594
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 594 is the Dataset Display Facility (DDF) from Roy        *   FILE 594
//*           Gardiner.  This is an ISPF-based workbench tool,      *   FILE 594
//*           to make it easier to work on your own collection      *   FILE 594
//*           of datasets.                                          *   FILE 594
//*                                                                 *   FILE 594
//*           email:  roy@roygardiner.com                           *   FILE 594
//*                                                                 *   FILE 594
//*      Introduction to DDF                                        *   FILE 594
//*                                                                 *   FILE 594
//*           Dataset Display Facility (DDF)                        *   FILE 594
//*                                                                 *   FILE 594
//*           DDF maintains a user-controlled list of dataset       *   FILE 594
//*           names against which many standard operations may      *   FILE 594
//*           be done.  It eliminates the constant typing and       *   FILE 594
//*           re-typing of dataset names that ISPF users must       *   FILE 594
//*           normally do and significantly reduces the number      *   FILE 594
//*           of 'enter' keys needed for some common operations.    *   FILE 594
//*                                                                 *   FILE 594
//*           DDF is designed to save you time.  Almost all the     *   FILE 594
//*           ISPF functions you need to perform against            *   FILE 594
//*           datasets can be done faster from a DDF screen than    *   FILE 594
//*           from a standard ISPF menu; habitual users keep the    *   FILE 594
//*           DDF screen in use instead of an ISPF main menu.       *   FILE 594
//*                                                                 *   FILE 594
//*           functions provided include:                           *   FILE 594
//*                                                                 *   FILE 594
//*           -edit a dataset (or member)                           *   FILE 594
//*           -browse a dataset (or member)                         *   FILE 594
//*           -display and edit member stats                        *   FILE 594
//*           -compare members                                      *   FILE 594
//*           -copy a member from one dataset to another            *   FILE 594
//*             (optionally changing name)                          *   FILE 594
//*           -compare and merge members                            *   FILE 594
//*           -find versions of members across many datasets        *   FILE 594
//*           -submit jobs                                          *   FILE 594
//*           -access ISPF functions including 3.1, 3.2, 3.3,       *   FILE 594
//*                                            3.4, 3.14            *   FILE 594
//*           -produce member list and then within member list:     *   FILE 594
//*                submit batch job                                 *   FILE 594
//*                browse member                                    *   FILE 594
//*                edit member                                      *   FILE 594
//*                rename member                                    *   FILE 594
//*                delete member                                    *   FILE 594
//*                execute member                                   *   FILE 594
//*                                                                 *   FILE 594
//*        What is DDF?                                             *   FILE 594
//*                                                                 *   FILE 594
//*        DDF is a Rexx exec and some ISPF panels, skeletons       *   FILE 594
//*        and messages. There is no Assembler and no need to       *   FILE 594
//*        complile anything. There are no tricks or dodges; all    *   FILE 594
//*        DDF functions are standard ISPF which you can see        *   FILE 594
//*        (and modify if you need to) in the code.                 *   FILE 594
//*                                                                 *   FILE 594
//*             You do not need to be a systems programmer to       *   FILE 594
//*        install DDF; anyone with modest knowledge of ISPF can    *   FILE 594
//*        set it up for personal use, or for use by more than      *   FILE 594
//*        one person. DDF does not interfere with your ISPF        *   FILE 594
//*        environment beyond requiring one exec to be copied to    *   FILE 594
//*        a suitable command library. All other DDF libraries      *   FILE 594
//*        remain separate from and therefore independent of        *   FILE 594
//*        your standard session, and indeed are only available     *   FILE 594
//*        whilst DDF is running - DDF uses LIBDEF to gain          *   FILE 594
//*        access to them.                                          *   FILE 594
//*                                                                 *   FILE 594
//*        Who uses DDF?                                            *   FILE 594
//*                                                                 *   FILE 594
//*        When DDF is made widely available, experience shows      *   FILE 594
//*        that that up to 10% of a typical TSO/ISPF user           *   FILE 594
//*        population will use it every day; some of these will     *   FILE 594
//*        use DDF as their standard front screen, rather than      *   FILE 594
//*        having an ISPF main menu. The main users seem            *   FILE 594
//*        generally to be to be development people rather than     *   FILE 594
//*        systems programmers; the latter have often written       *   FILE 594
//*        any number of shortcuts and tools for themselves and     *   FILE 594
//*        have their working environments tailored perfectly to    *   FILE 594
//*        suit them.                                               *   FILE 594
//*                                                                 *   FILE 594
```
