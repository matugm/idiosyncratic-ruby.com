---
title: The Constant Tree
date: 2016-05-22
tags: core, constants
commit: ff20753adf4e143c64cfc55bd2f71c7975b7956c
---

Generated with Ruby 2.4.0, including RubyGems and [DidYouMean](http://idiosyncratic-ruby.com/20-better-standards.html#bundled-gems):

<pre id="constant-tree">Object (Class)
├─ARGF (ARGF.class)
├─ARGV (Array)
├─ArgumentError (Class)
├─Array (Class)
├─BasicObject (Class)
│ └─BasicObject → BasicObject
├─Bignum (Class)
│ └─GMP_VERSION (String)
├─Binding (Class)
├─CROSS_COMPILING (NilClass)
├─Class (Class)
├─ClosedQueueError (Class)
├─Comparable (Module)
├─Complex (Class)
│ └─I (Complex)
├─ConditionVariable (Class)
├─Data (Class)
├─DidYouMean (Module)
├─Dir (Class)
├─ENV (Object)
├─EOFError (Class)
├─Encoding (Class)
│ ├─ANSI_X3_4_1968 (Encoding)
│ ├─ASCII (Encoding)
│ ├─ASCII_8BIT (Encoding)
│ ├─BIG5 (Encoding)
│ ├─BIG5_HKSCS (Encoding)
│ ├─BIG5_HKSCS_2008 (Encoding)
│ ├─BIG5_UAO (Encoding)
│ ├─BINARY (Encoding)
│ ├─Big5 (Encoding)
│ ├─Big5_HKSCS (Encoding)
│ ├─Big5_HKSCS_2008 (Encoding)
│ ├─Big5_UAO (Encoding)
│ ├─CP1250 (Encoding)
│ ├─CP1251 (Encoding)
│ ├─CP1252 (Encoding)
│ ├─CP1253 (Encoding)
│ ├─CP1254 (Encoding)
│ ├─CP1255 (Encoding)
│ ├─CP1256 (Encoding)
│ ├─CP1257 (Encoding)
│ ├─CP1258 (Encoding)
│ ├─CP437 (Encoding)
│ ├─CP50220 (Encoding)
│ ├─CP50221 (Encoding)
│ ├─CP51932 (Encoding)
│ ├─CP65000 (Encoding)
│ ├─CP65001 (Encoding)
│ ├─CP737 (Encoding)
│ ├─CP775 (Encoding)
│ ├─CP850 (Encoding)
│ ├─CP852 (Encoding)
│ ├─CP855 (Encoding)
│ ├─CP857 (Encoding)
│ ├─CP860 (Encoding)
│ ├─CP861 (Encoding)
│ ├─CP862 (Encoding)
│ ├─CP863 (Encoding)
│ ├─CP864 (Encoding)
│ ├─CP865 (Encoding)
│ ├─CP866 (Encoding)
│ ├─CP869 (Encoding)
│ ├─CP874 (Encoding)
│ ├─CP878 (Encoding)
│ ├─CP932 (Encoding)
│ ├─CP936 (Encoding)
│ ├─CP949 (Encoding)
│ ├─CP950 (Encoding)
│ ├─CP951 (Encoding)
│ ├─CSWINDOWS31J (Encoding)
│ ├─CompatibilityError (Class)
│ ├─Converter (Class)
│ │ ├─AFTER_OUTPUT (Integer)
│ │ ├─CRLF_NEWLINE_DECORATOR (Integer)
│ │ ├─CR_NEWLINE_DECORATOR (Integer)
│ │ ├─INVALID_MASK (Integer)
│ │ ├─INVALID_REPLACE (Integer)
│ │ ├─PARTIAL_INPUT (Integer)
│ │ ├─UNDEF_HEX_CHARREF (Integer)
│ │ ├─UNDEF_MASK (Integer)
│ │ ├─UNDEF_REPLACE (Integer)
│ │ ├─UNIVERSAL_NEWLINE_DECORATOR (Integer)
│ │ ├─XML_ATTR_CONTENT_DECORATOR (Integer)
│ │ ├─XML_ATTR_QUOTE_DECORATOR (Integer)
│ │ └─XML_TEXT_DECORATOR (Integer)
│ ├─ConverterNotFoundError (Class)
│ ├─CsWindows31J (Encoding)
│ ├─EBCDIC_CP_US (Encoding)
│ ├─EMACS_MULE (Encoding)
│ ├─EUCCN (Encoding)
│ ├─EUCJP (Encoding)
│ ├─EUCJP_MS (Encoding)
│ ├─EUCKR (Encoding)
│ ├─EUCTW (Encoding)
│ ├─EUC_CN (Encoding)
│ ├─EUC_JISX0213 (Encoding)
│ ├─EUC_JIS_2004 (Encoding)
│ ├─EUC_JP (Encoding)
│ ├─EUC_JP_MS (Encoding)
│ ├─EUC_KR (Encoding)
│ ├─EUC_TW (Encoding)
│ ├─Emacs_Mule (Encoding)
│ ├─EucCN (Encoding)
│ ├─EucJP (Encoding)
│ ├─EucJP_ms (Encoding)
│ ├─EucKR (Encoding)
│ ├─EucTW (Encoding)
│ ├─GB12345 (Encoding)
│ ├─GB18030 (Encoding)
│ ├─GB1988 (Encoding)
│ ├─GB2312 (Encoding)
│ ├─GBK (Encoding)
│ ├─IBM037 (Encoding)
│ ├─IBM437 (Encoding)
│ ├─IBM737 (Encoding)
│ ├─IBM775 (Encoding)
│ ├─IBM850 (Encoding)
│ ├─IBM852 (Encoding)
│ ├─IBM855 (Encoding)
│ ├─IBM857 (Encoding)
│ ├─IBM860 (Encoding)
│ ├─IBM861 (Encoding)
│ ├─IBM862 (Encoding)
│ ├─IBM863 (Encoding)
│ ├─IBM864 (Encoding)
│ ├─IBM865 (Encoding)
│ ├─IBM866 (Encoding)
│ ├─IBM869 (Encoding)
│ ├─ISO2022_JP (Encoding)
│ ├─ISO2022_JP2 (Encoding)
│ ├─ISO8859_1 (Encoding)
│ ├─ISO8859_10 (Encoding)
│ ├─ISO8859_11 (Encoding)
│ ├─ISO8859_13 (Encoding)
│ ├─ISO8859_14 (Encoding)
│ ├─ISO8859_15 (Encoding)
│ ├─ISO8859_16 (Encoding)
│ ├─ISO8859_2 (Encoding)
│ ├─ISO8859_3 (Encoding)
│ ├─ISO8859_4 (Encoding)
│ ├─ISO8859_5 (Encoding)
│ ├─ISO8859_6 (Encoding)
│ ├─ISO8859_7 (Encoding)
│ ├─ISO8859_8 (Encoding)
│ ├─ISO8859_9 (Encoding)
│ ├─ISO_2022_JP (Encoding)
│ ├─ISO_2022_JP_2 (Encoding)
│ ├─ISO_2022_JP_KDDI (Encoding)
│ ├─ISO_8859_1 (Encoding)
│ ├─ISO_8859_10 (Encoding)
│ ├─ISO_8859_11 (Encoding)
│ ├─ISO_8859_13 (Encoding)
│ ├─ISO_8859_14 (Encoding)
│ ├─ISO_8859_15 (Encoding)
│ ├─ISO_8859_16 (Encoding)
│ ├─ISO_8859_2 (Encoding)
│ ├─ISO_8859_3 (Encoding)
│ ├─ISO_8859_4 (Encoding)
│ ├─ISO_8859_5 (Encoding)
│ ├─ISO_8859_6 (Encoding)
│ ├─ISO_8859_7 (Encoding)
│ ├─ISO_8859_8 (Encoding)
│ ├─ISO_8859_9 (Encoding)
│ ├─InvalidByteSequenceError (Class)
│ ├─KOI8_R (Encoding)
│ ├─KOI8_U (Encoding)
│ ├─MACCENTEURO (Encoding)
│ ├─MACCROATIAN (Encoding)
│ ├─MACCYRILLIC (Encoding)
│ ├─MACGREEK (Encoding)
│ ├─MACICELAND (Encoding)
│ ├─MACJAPAN (Encoding)
│ ├─MACJAPANESE (Encoding)
│ ├─MACROMAN (Encoding)
│ ├─MACROMANIA (Encoding)
│ ├─MACTHAI (Encoding)
│ ├─MACTURKISH (Encoding)
│ ├─MACUKRAINE (Encoding)
│ ├─MacCentEuro (Encoding)
│ ├─MacCroatian (Encoding)
│ ├─MacCyrillic (Encoding)
│ ├─MacGreek (Encoding)
│ ├─MacIceland (Encoding)
│ ├─MacJapan (Encoding)
│ ├─MacJapanese (Encoding)
│ ├─MacRoman (Encoding)
│ ├─MacRomania (Encoding)
│ ├─MacThai (Encoding)
│ ├─MacTurkish (Encoding)
│ ├─MacUkraine (Encoding)
│ ├─PCK (Encoding)
│ ├─SHIFT_JIS (Encoding)
│ ├─SJIS (Encoding)
│ ├─SJIS_DOCOMO (Encoding)
│ ├─SJIS_DoCoMo (Encoding)
│ ├─SJIS_KDDI (Encoding)
│ ├─SJIS_SOFTBANK (Encoding)
│ ├─SJIS_SoftBank (Encoding)
│ ├─STATELESS_ISO_2022_JP (Encoding)
│ ├─STATELESS_ISO_2022_JP_KDDI (Encoding)
│ ├─Shift_JIS (Encoding)
│ ├─Stateless_ISO_2022_JP (Encoding)
│ ├─Stateless_ISO_2022_JP_KDDI (Encoding)
│ ├─TIS_620 (Encoding)
│ ├─UCS_2BE (Encoding)
│ ├─UCS_4BE (Encoding)
│ ├─UCS_4LE (Encoding)
│ ├─US_ASCII (Encoding)
│ ├─UTF8_DOCOMO (Encoding)
│ ├─UTF8_DoCoMo (Encoding)
│ ├─UTF8_KDDI (Encoding)
│ ├─UTF8_MAC (Encoding)
│ ├─UTF8_SOFTBANK (Encoding)
│ ├─UTF8_SoftBank (Encoding)
│ ├─UTF_16 (Encoding)
│ ├─UTF_16BE (Encoding)
│ ├─UTF_16LE (Encoding)
│ ├─UTF_32 (Encoding)
│ ├─UTF_32BE (Encoding)
│ ├─UTF_32LE (Encoding)
│ ├─UTF_7 (Encoding)
│ ├─UTF_8 (Encoding)
│ ├─UTF_8_HFS (Encoding)
│ ├─UTF_8_MAC (Encoding)
│ ├─UndefinedConversionError (Class)
│ ├─WINDOWS_1250 (Encoding)
│ ├─WINDOWS_1251 (Encoding)
│ ├─WINDOWS_1252 (Encoding)
│ ├─WINDOWS_1253 (Encoding)
│ ├─WINDOWS_1254 (Encoding)
│ ├─WINDOWS_1255 (Encoding)
│ ├─WINDOWS_1256 (Encoding)
│ ├─WINDOWS_1257 (Encoding)
│ ├─WINDOWS_1258 (Encoding)
│ ├─WINDOWS_31J (Encoding)
│ ├─WINDOWS_874 (Encoding)
│ ├─Windows_1250 (Encoding)
│ ├─Windows_1251 (Encoding)
│ ├─Windows_1252 (Encoding)
│ ├─Windows_1253 (Encoding)
│ ├─Windows_1254 (Encoding)
│ ├─Windows_1255 (Encoding)
│ ├─Windows_1256 (Encoding)
│ ├─Windows_1257 (Encoding)
│ ├─Windows_1258 (Encoding)
│ ├─Windows_31J (Encoding)
│ └─Windows_874 (Encoding)
├─EncodingError (Class)
├─Enumerable (Module)
├─Enumerator (Class)
│ ├─Generator (Class)
│ ├─Lazy (Class)
│ └─Yielder (Class)
├─Errno (Module)
│ ├─E2BIG (Class)
│ │ └─Errno (Integer)
│ ├─EACCES (Class)
│ │ └─Errno (Integer)
│ ├─EADDRINUSE (Class)
│ │ └─Errno (Integer)
│ ├─EADDRNOTAVAIL (Class)
│ │ └─Errno (Integer)
│ ├─EADV (Class)
│ │ └─Errno (Integer)
│ ├─EAFNOSUPPORT (Class)
│ │ └─Errno (Integer)
│ ├─EAGAIN (Class)
│ │ └─Errno (Integer)
│ ├─EALREADY (Class)
│ │ └─Errno (Integer)
│ ├─EAUTH (Class)
│ │ └─Errno (Integer)
│ ├─EBADE (Class)
│ │ └─Errno (Integer)
│ ├─EBADF (Class)
│ │ └─Errno (Integer)
│ ├─EBADFD (Class)
│ │ └─Errno (Integer)
│ ├─EBADMSG (Class)
│ │ └─Errno (Integer)
│ ├─EBADR (Class)
│ │ └─Errno (Integer)
│ ├─EBADRPC (Class)
│ │ └─Errno (Integer)
│ ├─EBADRQC (Class)
│ │ └─Errno (Integer)
│ ├─EBADSLT (Class)
│ │ └─Errno (Integer)
│ ├─EBFONT (Class)
│ │ └─Errno (Integer)
│ ├─EBUSY (Class)
│ │ └─Errno (Integer)
│ ├─ECANCELED (Class)
│ │ └─Errno (Integer)
│ ├─ECAPMODE (Class)
│ │ └─Errno (Integer)
│ ├─ECHILD (Class)
│ │ └─Errno (Integer)
│ ├─ECHRNG (Class)
│ │ └─Errno (Integer)
│ ├─ECOMM (Class)
│ │ └─Errno (Integer)
│ ├─ECONNABORTED (Class)
│ │ └─Errno (Integer)
│ ├─ECONNREFUSED (Class)
│ │ └─Errno (Integer)
│ ├─ECONNRESET (Class)
│ │ └─Errno (Integer)
│ ├─EDEADLK (Class)
│ │ └─Errno (Integer)
│ ├─EDEADLOCK (Class)
│ │ └─Errno (Integer)
│ ├─EDESTADDRREQ (Class)
│ │ └─Errno (Integer)
│ ├─EDOM (Class)
│ │ └─Errno (Integer)
│ ├─EDOOFUS (Class)
│ │ └─Errno (Integer)
│ ├─EDOTDOT (Class)
│ │ └─Errno (Integer)
│ ├─EDQUOT (Class)
│ │ └─Errno (Integer)
│ ├─EEXIST (Class)
│ │ └─Errno (Integer)
│ ├─EFAULT (Class)
│ │ └─Errno (Integer)
│ ├─EFBIG (Class)
│ │ └─Errno (Integer)
│ ├─EFTYPE (Class)
│ │ └─Errno (Integer)
│ ├─EHOSTDOWN (Class)
│ │ └─Errno (Integer)
│ ├─EHOSTUNREACH (Class)
│ │ └─Errno (Integer)
│ ├─EHWPOISON (Class)
│ │ └─Errno (Integer)
│ ├─EIDRM (Class)
│ │ └─Errno (Integer)
│ ├─EILSEQ (Class)
│ │ └─Errno (Integer)
│ ├─EINPROGRESS (Class)
│ │ └─Errno (Integer)
│ ├─EINTR (Class)
│ │ └─Errno (Integer)
│ ├─EINVAL (Class)
│ │ └─Errno (Integer)
│ ├─EIO (Class)
│ │ └─Errno (Integer)
│ ├─EIPSEC (Class)
│ │ └─Errno (Integer)
│ ├─EISCONN (Class)
│ │ └─Errno (Integer)
│ ├─EISDIR (Class)
│ │ └─Errno (Integer)
│ ├─EISNAM (Class)
│ │ └─Errno (Integer)
│ ├─EKEYEXPIRED (Class)
│ │ └─Errno (Integer)
│ ├─EKEYREJECTED (Class)
│ │ └─Errno (Integer)
│ ├─EKEYREVOKED (Class)
│ │ └─Errno (Integer)
│ ├─EL2HLT (Class)
│ │ └─Errno (Integer)
│ ├─EL2NSYNC (Class)
│ │ └─Errno (Integer)
│ ├─EL3HLT (Class)
│ │ └─Errno (Integer)
│ ├─EL3RST (Class)
│ │ └─Errno (Integer)
│ ├─ELIBACC (Class)
│ │ └─Errno (Integer)
│ ├─ELIBBAD (Class)
│ │ └─Errno (Integer)
│ ├─ELIBEXEC (Class)
│ │ └─Errno (Integer)
│ ├─ELIBMAX (Class)
│ │ └─Errno (Integer)
│ ├─ELIBSCN (Class)
│ │ └─Errno (Integer)
│ ├─ELNRNG (Class)
│ │ └─Errno (Integer)
│ ├─ELOOP (Class)
│ │ └─Errno (Integer)
│ ├─EMEDIUMTYPE (Class)
│ │ └─Errno (Integer)
│ ├─EMFILE (Class)
│ │ └─Errno (Integer)
│ ├─EMLINK (Class)
│ │ └─Errno (Integer)
│ ├─EMSGSIZE (Class)
│ │ └─Errno (Integer)
│ ├─EMULTIHOP (Class)
│ │ └─Errno (Integer)
│ ├─ENAMETOOLONG (Class)
│ │ └─Errno (Integer)
│ ├─ENAVAIL (Class)
│ │ └─Errno (Integer)
│ ├─ENEEDAUTH (Class)
│ │ └─Errno (Integer)
│ ├─ENETDOWN (Class)
│ │ └─Errno (Integer)
│ ├─ENETRESET (Class)
│ │ └─Errno (Integer)
│ ├─ENETUNREACH (Class)
│ │ └─Errno (Integer)
│ ├─ENFILE (Class)
│ │ └─Errno (Integer)
│ ├─ENOANO (Class)
│ │ └─Errno (Integer)
│ ├─ENOATTR (Class)
│ │ └─Errno (Integer)
│ ├─ENOBUFS (Class)
│ │ └─Errno (Integer)
│ ├─ENOCSI (Class)
│ │ └─Errno (Integer)
│ ├─ENODATA (Class)
│ │ └─Errno (Integer)
│ ├─ENODEV (Class)
│ │ └─Errno (Integer)
│ ├─ENOENT (Class)
│ │ └─Errno (Integer)
│ ├─ENOEXEC (Class)
│ │ └─Errno (Integer)
│ ├─ENOKEY (Class)
│ │ └─Errno (Integer)
│ ├─ENOLCK (Class)
│ │ └─Errno (Integer)
│ ├─ENOLINK (Class)
│ │ └─Errno (Integer)
│ ├─ENOMEDIUM (Class)
│ │ └─Errno (Integer)
│ ├─ENOMEM (Class)
│ │ └─Errno (Integer)
│ ├─ENOMSG (Class)
│ │ └─Errno (Integer)
│ ├─ENONET (Class)
│ │ └─Errno (Integer)
│ ├─ENOPKG (Class)
│ │ └─Errno (Integer)
│ ├─ENOPROTOOPT (Class)
│ │ └─Errno (Integer)
│ ├─ENOSPC (Class)
│ │ └─Errno (Integer)
│ ├─ENOSR (Class)
│ │ └─Errno (Integer)
│ ├─ENOSTR (Class)
│ │ └─Errno (Integer)
│ ├─ENOSYS (Class)
│ │ └─Errno (Integer)
│ ├─ENOTBLK (Class)
│ │ └─Errno (Integer)
│ ├─ENOTCAPABLE (Class)
│ │ └─Errno (Integer)
│ ├─ENOTCONN (Class)
│ │ └─Errno (Integer)
│ ├─ENOTDIR (Class)
│ │ └─Errno (Integer)
│ ├─ENOTEMPTY (Class)
│ │ └─Errno (Integer)
│ ├─ENOTNAM (Class)
│ │ └─Errno (Integer)
│ ├─ENOTRECOVERABLE (Class)
│ │ └─Errno (Integer)
│ ├─ENOTSOCK (Class)
│ │ └─Errno (Integer)
│ ├─ENOTSUP (Class)
│ │ └─Errno (Integer)
│ ├─ENOTTY (Class)
│ │ └─Errno (Integer)
│ ├─ENOTUNIQ (Class)
│ │ └─Errno (Integer)
│ ├─ENXIO (Class)
│ │ └─Errno (Integer)
│ ├─EOPNOTSUPP (Class)
│ │ └─Errno (Integer)
│ ├─EOVERFLOW (Class)
│ │ └─Errno (Integer)
│ ├─EOWNERDEAD (Class)
│ │ └─Errno (Integer)
│ ├─EPERM (Class)
│ │ └─Errno (Integer)
│ ├─EPFNOSUPPORT (Class)
│ │ └─Errno (Integer)
│ ├─EPIPE (Class)
│ │ └─Errno (Integer)
│ ├─EPROCLIM (Class)
│ │ └─Errno (Integer)
│ ├─EPROCUNAVAIL (Class)
│ │ └─Errno (Integer)
│ ├─EPROGMISMATCH (Class)
│ │ └─Errno (Integer)
│ ├─EPROGUNAVAIL (Class)
│ │ └─Errno (Integer)
│ ├─EPROTO (Class)
│ │ └─Errno (Integer)
│ ├─EPROTONOSUPPORT (Class)
│ │ └─Errno (Integer)
│ ├─EPROTOTYPE (Class)
│ │ └─Errno (Integer)
│ ├─ERANGE (Class)
│ │ └─Errno (Integer)
│ ├─EREMCHG (Class)
│ │ └─Errno (Integer)
│ ├─EREMOTE (Class)
│ │ └─Errno (Integer)
│ ├─EREMOTEIO (Class)
│ │ └─Errno (Integer)
│ ├─ERESTART (Class)
│ │ └─Errno (Integer)
│ ├─ERFKILL (Class)
│ │ └─Errno (Integer)
│ ├─EROFS (Class)
│ │ └─Errno (Integer)
│ ├─ERPCMISMATCH (Class)
│ │ └─Errno (Integer)
│ ├─ESHUTDOWN (Class)
│ │ └─Errno (Integer)
│ ├─ESOCKTNOSUPPORT (Class)
│ │ └─Errno (Integer)
│ ├─ESPIPE (Class)
│ │ └─Errno (Integer)
│ ├─ESRCH (Class)
│ │ └─Errno (Integer)
│ ├─ESRMNT (Class)
│ │ └─Errno (Integer)
│ ├─ESTALE (Class)
│ │ └─Errno (Integer)
│ ├─ESTRPIPE (Class)
│ │ └─Errno (Integer)
│ ├─ETIME (Class)
│ │ └─Errno (Integer)
│ ├─ETIMEDOUT (Class)
│ │ └─Errno (Integer)
│ ├─ETOOMANYREFS (Class)
│ │ └─Errno (Integer)
│ ├─ETXTBSY (Class)
│ │ └─Errno (Integer)
│ ├─EUCLEAN (Class)
│ │ └─Errno (Integer)
│ ├─EUNATCH (Class)
│ │ └─Errno (Integer)
│ ├─EUSERS (Class)
│ │ └─Errno (Integer)
│ ├─EWOULDBLOCK (Class)
│ │ └─Errno (Integer)
│ ├─EXDEV (Class)
│ │ └─Errno (Integer)
│ ├─EXFULL (Class)
│ │ └─Errno (Integer)
│ └─NOERROR (Class)
│   └─Errno (Integer)
├─Exception (Class)
├─FALSE (FalseClass)
├─FalseClass (Class)
├─Fiber (Class)
├─FiberError (Class)
├─File (Class)
│ ├─ALT_SEPARATOR (NilClass)
│ ├─Constants (Module)
│ │ ├─APPEND (Integer)
│ │ ├─BINARY (Integer)
│ │ ├─CREAT (Integer)
│ │ ├─DIRECT (Integer)
│ │ ├─DSYNC (Integer)
│ │ ├─EXCL (Integer)
│ │ ├─FNM_CASEFOLD (Integer)
│ │ ├─FNM_DOTMATCH (Integer)
│ │ ├─FNM_EXTGLOB (Integer)
│ │ ├─FNM_NOESCAPE (Integer)
│ │ ├─FNM_PATHNAME (Integer)
│ │ ├─FNM_SHORTNAME (Integer)
│ │ ├─FNM_SYSCASE (Integer)
│ │ ├─LOCK_EX (Integer)
│ │ ├─LOCK_NB (Integer)
│ │ ├─LOCK_SH (Integer)
│ │ ├─LOCK_UN (Integer)
│ │ ├─NOATIME (Integer)
│ │ ├─NOCTTY (Integer)
│ │ ├─NOFOLLOW (Integer)
│ │ ├─NONBLOCK (Integer)
│ │ ├─NULL (String)
│ │ ├─RDONLY (Integer)
│ │ ├─RDWR (Integer)
│ │ ├─RSYNC (Integer)
│ │ ├─SHARE_DELETE (Integer)
│ │ ├─SYNC (Integer)
│ │ ├─TMPFILE (Integer)
│ │ ├─TRUNC (Integer)
│ │ └─WRONLY (Integer)
│ ├─PATH_SEPARATOR (String)
│ ├─SEPARATOR (String)
│ ├─Separator (String)
│ └─Stat (Class)
├─FileTest (Module)
├─Fixnum (Class)
│ └─GMP_VERSION (String)
├─Float (Class)
│ ├─DIG (Integer)
│ ├─EPSILON (Float)
│ ├─INFINITY (Float)
│ ├─MANT_DIG (Integer)
│ ├─MAX (Float)
│ ├─MAX_10_EXP (Integer)
│ ├─MAX_EXP (Integer)
│ ├─MIN (Float)
│ ├─MIN_10_EXP (Integer)
│ ├─MIN_EXP (Integer)
│ ├─NAN (Float)
│ ├─RADIX (Integer)
│ └─ROUNDS (Integer)
├─FloatDomainError (Class)
├─GC (Module)
│ ├─INTERNAL_CONSTANTS (Hash)
│ ├─OPTS (Array)
│ └─Profiler (Module)
├─Gem (Module)
│ ├─BasicSpecification (Class)
│ ├─CommandLineError (Class)
│ ├─ConfigFile (Class)
│ │ ├─DEFAULT_BACKTRACE (FalseClass)
│ │ ├─DEFAULT_BULK_THRESHOLD (Integer)
│ │ ├─DEFAULT_UPDATE_SOURCES (TrueClass)
│ │ ├─DEFAULT_VERBOSITY (TrueClass)
│ │ ├─OPERATING_SYSTEM_DEFAULTS (Hash)
│ │ ├─PLATFORM_DEFAULTS (Hash)
│ │ ├─SYSTEM_CONFIG_PATH (String)
│ │ └─SYSTEM_WIDE_CONFIG_FILE (String)
│ ├─ConfigMap (Hash)
│ ├─ConflictError (Class)
│ ├─DEFAULT_HOST (String)
│ ├─Dependency (Class)
│ │ └─TYPES (Array)
│ ├─DependencyError (Class)
│ ├─DependencyList (Class)
│ ├─DependencyRemovalException (Class)
│ ├─DependencyResolutionError (Class)
│ ├─DependencyResolver (Class)
│ │ ├─APISet (Class)
│ │ ├─APISpecification (Class)
│ │ ├─ActivationRequest (Class)
│ │ ├─BestSet (Class)
│ │ ├─ComposedSet (Class)
│ │ ├─Conflict (Class)
│ │ ├─CurrentSet (Class)
│ │ ├─DEBUG_RESOLVER (FalseClass)
│ │ ├─DependencyConflict (Class)
│ │ ├─DependencyRequest (Class)
│ │ ├─GitSet (Class)
│ │ ├─GitSpecification (Class)
│ │ ├─IndexSet (Class)
│ │ ├─IndexSpecification (Class)
│ │ ├─InstalledSpecification (Class)
│ │ ├─InstallerSet (Class)
│ │ ├─LocalSpecification (Class)
│ │ ├─LockSet (Class)
│ │ ├─LockSpecification (Class)
│ │ ├─Molinillo (Module)
│ │ │ ├─CircularDependencyError (Class)
│ │ │ ├─Delegates (Module)
│ │ │ │ ├─ResolutionState (Module)
│ │ │ │ └─SpecificationProvider (Module)
│ │ │ ├─DependencyGraph (Class)
│ │ │ │ ├─Action (Class)
│ │ │ │ ├─AddEdgeNoCircular (Class)
│ │ │ │ ├─AddVertex (Class)
│ │ │ │ ├─DeleteEdge (Class)
│ │ │ │ ├─DetachVertexNamed (Class)
│ │ │ │ ├─Edge (Class)
│ │ │ │ ├─Log (Class)
│ │ │ │ ├─SetPayload (Class)
│ │ │ │ ├─Tag (Class)
│ │ │ │ └─Vertex (Class)
│ │ │ ├─DependencyState (Class)
│ │ │ ├─NoSuchDependencyError (Class)
│ │ │ ├─PossibilityState (Class)
│ │ │ ├─ResolutionState (Class)
│ │ │ ├─Resolver (Class)
│ │ │ │ └─Resolution (Class)
│ │ │ │   └─Conflict (Class)
│ │ │ ├─ResolverError (Class)
│ │ │ ├─SpecificationProvider (Module)
│ │ │ ├─UI (Module)
│ │ │ ├─VERSION (String)
│ │ │ └─VersionConflict (Class)
│ │ ├─RequirementList (Class)
│ │ ├─Set (Class)
│ │ ├─SourceSet (Class)
│ │ ├─SpecSpecification (Class)
│ │ ├─Specification (Class)
│ │ ├─Stats (Class)
│ │ │ └─PATTERN (String)
│ │ ├─VendorSet (Class)
│ │ └─VendorSpecification (Class)
│ ├─Deprecate (Module)
│ ├─DocumentError (Class)
│ ├─EndOfYAMLException (Class)
│ ├─ErrorReason (Class)
│ ├─Exception (Class)
│ ├─FilePermissionError (Class)
│ ├─FormatException (Class)
│ ├─GEM_DEP_FILES (Array)
│ ├─GEM_PRELUDE_SUCKAGE (NilClass)
│ ├─GemNotFoundException (Class)
│ ├─GemNotInHomeException (Class)
│ ├─ImpossibleDependenciesError (Class)
│ ├─InstallError (Class)
│ ├─Installer (Class)
│ │ ├─ENV_PATHS (Array)
│ │ ├─ExtensionBuildError (Class)
│ │ └─FakePackage (Class)
│ ├─InvalidSpecificationException (Class)
│ ├─LOADED_SPECS_MUTEX (Thread::Mutex)
│ ├─Licenses (Class)
│ │ ├─IDENTIFIERS (Array)
│ │ ├─NONSTANDARD (String)
│ │ └─REGEXP (Regexp)
│ ├─List (Class)
│ ├─LoadError (Class)
│ ├─MARSHAL_SPEC_DIR (String)
│ ├─MissingSpecError (Class)
│ ├─MissingSpecVersionError (Class)
│ ├─OperationNotSupportedError (Class)
│ ├─PathSupport (Class)
│ ├─Platform (Class)
│ │ ├─CURRENT (String)
│ │ └─RUBY (String)
│ ├─PlatformMismatch (Class)
│ ├─READ_BINARY_ERRORS (Array)
│ ├─REPOSITORY_DEFAULT_GEM_SUBDIRECTORIES (Array)
│ ├─REPOSITORY_SUBDIRECTORIES (Array)
│ ├─RUBYGEMS_DIR (String)
│ ├─RbConfigPriorities (Array)
│ ├─RemoteError (Class)
│ ├─RemoteInstallationCancelled (Class)
│ ├─RemoteInstallationSkipped (Class)
│ ├─RemoteSourceException (Class)
│ ├─RequestSet (Class)
│ │ ├─GemDepedencyAPI (Class)
│ │ │ ├─ENGINE_MAP (Hash)
│ │ │ ├─PLATFORM_MAP (Hash)
│ │ │ ├─VERSION_MAP (Hash)
│ │ │ └─WINDOWS (Hash)
│ │ ├─GemDependencyAPI (Class)
│ │ │ ├─ENGINE_MAP (Hash)
│ │ │ ├─PLATFORM_MAP (Hash)
│ │ │ ├─VERSION_MAP (Hash)
│ │ │ └─WINDOWS (Hash)
│ │ └─Lockfile (Class)
│ │   ├─ParseError (Class)
│ │   ├─Parser (Class)
│ │   └─Tokenizer (Class)
│ │     ├─EOF (Gem::RequestSet::Lockfile::Tokenizer::Token)
│ │     └─Token (Class)
│ ├─Requirement (Class)
│ │ ├─BadRequirementError (Class)
│ │ ├─DefaultRequirement (Array)
│ │ ├─OPS (Hash)
│ │ ├─PATTERN (Regexp)
│ │ ├─PATTERN_RAW (String)
│ │ └─SOURCE_SET_REQUIREMENT (#&lt;Class:0x0055eab356bd48&gt;)
│ ├─Resolver (Class)
│ │ ├─APISet (Class)
│ │ ├─APISpecification (Class)
│ │ ├─ActivationRequest (Class)
│ │ ├─BestSet (Class)
│ │ ├─ComposedSet (Class)
│ │ ├─Conflict (Class)
│ │ ├─CurrentSet (Class)
│ │ ├─DEBUG_RESOLVER (FalseClass)
│ │ ├─DependencyConflict (Class)
│ │ ├─DependencyRequest (Class)
│ │ ├─GitSet (Class)
│ │ ├─GitSpecification (Class)
│ │ ├─IndexSet (Class)
│ │ ├─IndexSpecification (Class)
│ │ ├─InstalledSpecification (Class)
│ │ ├─InstallerSet (Class)
│ │ ├─LocalSpecification (Class)
│ │ ├─LockSet (Class)
│ │ ├─LockSpecification (Class)
│ │ ├─Molinillo (Module)
│ │ │ ├─CircularDependencyError (Class)
│ │ │ ├─Delegates (Module)
│ │ │ │ ├─ResolutionState (Module)
│ │ │ │ └─SpecificationProvider (Module)
│ │ │ ├─DependencyGraph (Class)
│ │ │ │ ├─Action (Class)
│ │ │ │ ├─AddEdgeNoCircular (Class)
│ │ │ │ ├─AddVertex (Class)
│ │ │ │ ├─DeleteEdge (Class)
│ │ │ │ ├─DetachVertexNamed (Class)
│ │ │ │ ├─Edge (Class)
│ │ │ │ ├─Log (Class)
│ │ │ │ ├─SetPayload (Class)
│ │ │ │ ├─Tag (Class)
│ │ │ │ └─Vertex (Class)
│ │ │ ├─DependencyState (Class)
│ │ │ ├─NoSuchDependencyError (Class)
│ │ │ ├─PossibilityState (Class)
│ │ │ ├─ResolutionState (Class)
│ │ │ ├─Resolver (Class)
│ │ │ │ └─Resolution (Class)
│ │ │ │   └─Conflict (Class)
│ │ │ ├─ResolverError (Class)
│ │ │ ├─SpecificationProvider (Module)
│ │ │ ├─UI (Module)
│ │ │ ├─VERSION (String)
│ │ │ └─VersionConflict (Class)
│ │ ├─RequirementList (Class)
│ │ ├─Set (Class)
│ │ ├─SourceSet (Class)
│ │ ├─SpecSpecification (Class)
│ │ ├─Specification (Class)
│ │ ├─Stats (Class)
│ │ │ └─PATTERN (String)
│ │ ├─VendorSet (Class)
│ │ └─VendorSpecification (Class)
│ ├─RubyGemsPackageVersion (String)
│ ├─RubyGemsVersion (String)
│ ├─RubyVersionMismatch (Class)
│ ├─Source (Class)
│ │ ├─FILES (Hash)
│ │ ├─Git (Class)
│ │ ├─Installed (Class)
│ │ ├─Local (Class)
│ │ ├─Lock (Class)
│ │ ├─SpecificFile (Class)
│ │ └─Vendor (Class)
│ ├─SourceFetchProblem (Class)
│ ├─SourceList (Class)
│ ├─SpecFetcher (Class)
│ ├─SpecificGemNotFoundException (Class)
│ ├─Specification (Class)
│ │ ├─CURRENT_SPECIFICATION_VERSION (Integer)
│ │ ├─DateLike (Object)
│ │ ├─DateTimeFormat (Regexp)
│ │ ├─Dupable (Hash)
│ │ ├─EMPTY (Array)
│ │ ├─MARSHAL_FIELDS (Hash)
│ │ ├─NONEXISTENT_SPECIFICATION_VERSION (Integer)
│ │ ├─NOT_FOUND (#&lt;Class:0x0055eab34b9b20&gt;)
│ │ ├─SPECIFICATION_VERSION_HISTORY (Hash)
│ │ └─TODAY (Time)
│ ├─StubSpecification (Class)
│ │ ├─OPEN_MODE (String)
│ │ ├─PREFIX (String)
│ │ └─StubLine (Class)
│ │   ├─NO_EXTENSIONS (Array)
│ │   ├─REQUIRE_PATHS (Hash)
│ │   └─REQUIRE_PATH_LIST (Hash)
│ ├─SystemExitException (Class)
│ ├─UnsatisfiableDepedencyError (Class)
│ ├─UnsatisfiableDependencyError (Class)
│ ├─VERSION (String)
│ ├─VerificationError (Class)
│ ├─Version (Class)
│ │ ├─ANCHORED_VERSION_PATTERN (Regexp)
│ │ ├─Requirement (Class)
│ │ │ ├─BadRequirementError (Class)
│ │ │ ├─DefaultRequirement (Array)
│ │ │ ├─OPS (Hash)
│ │ │ ├─PATTERN (Regexp)
│ │ │ ├─PATTERN_RAW (String)
│ │ │ └─SOURCE_SET_REQUIREMENT (#&lt;Class:0x0055eab356bd48&gt;)
│ │ └─VERSION_PATTERN (String)
│ ├─WIN_PATTERNS (Array)
│ └─WRITE_BINARY_ERRORS (Array)
├─Hash (Class)
├─IO (Class)
│ ├─EAGAINWaitReadable (Class)
│ ├─EAGAINWaitWritable (Class)
│ ├─EINPROGRESSWaitReadable (Class)
│ ├─EINPROGRESSWaitWritable (Class)
│ ├─EWOULDBLOCKWaitReadable (Class)
│ ├─EWOULDBLOCKWaitWritable (Class)
│ ├─SEEK_CUR (Integer)
│ ├─SEEK_DATA (Integer)
│ ├─SEEK_END (Integer)
│ ├─SEEK_HOLE (Integer)
│ ├─SEEK_SET (Integer)
│ ├─WaitReadable (Module)
│ └─WaitWritable (Module)
├─IOError (Class)
├─IndexError (Class)
├─Integer (Class)
│ └─GMP_VERSION (String)
├─Interrupt (Class)
├─Kernel (Module)
│ └─RUBYGEMS_ACTIVATION_MONITOR (Monitor)
├─KeyError (Class)
├─LoadError (Class)
├─LocalJumpError (Class)
├─Marshal (Module)
│ ├─MAJOR_VERSION (Integer)
│ └─MINOR_VERSION (Integer)
├─MatchData (Class)
├─Math (Module)
│ ├─DomainError (Class)
│ ├─E (Float)
│ └─PI (Float)
├─Method (Class)
├─Module (Class)
├─Monitor (Class)
├─MonitorMixin (Module)
│ └─ConditionVariable (Class)
│   └─Timeout (Class)
├─Mutex (Class)
├─NIL (NilClass)
├─NameError (Class)
├─NilClass (Class)
├─NoMemoryError (Class)
├─NoMethodError (Class)
├─NotImplementedError (Class)
├─Numeric (Class)
├─Object → Object
├─ObjectSpace (Module)
│ └─WeakMap (Class)
├─Proc (Class)
├─Process (Module)
│ ├─CLOCK_BOOTTIME (Integer)
│ ├─CLOCK_BOOTTIME_ALARM (Integer)
│ ├─CLOCK_MONOTONIC (Integer)
│ ├─CLOCK_MONOTONIC_COARSE (Integer)
│ ├─CLOCK_MONOTONIC_RAW (Integer)
│ ├─CLOCK_PROCESS_CPUTIME_ID (Integer)
│ ├─CLOCK_REALTIME (Integer)
│ ├─CLOCK_REALTIME_ALARM (Integer)
│ ├─CLOCK_REALTIME_COARSE (Integer)
│ ├─CLOCK_THREAD_CPUTIME_ID (Integer)
│ ├─GID (Module)
│ ├─PRIO_PGRP (Integer)
│ ├─PRIO_PROCESS (Integer)
│ ├─PRIO_USER (Integer)
│ ├─RLIMIT_AS (Integer)
│ ├─RLIMIT_CORE (Integer)
│ ├─RLIMIT_CPU (Integer)
│ ├─RLIMIT_DATA (Integer)
│ ├─RLIMIT_FSIZE (Integer)
│ ├─RLIMIT_MEMLOCK (Integer)
│ ├─RLIMIT_MSGQUEUE (Integer)
│ ├─RLIMIT_NICE (Integer)
│ ├─RLIMIT_NOFILE (Integer)
│ ├─RLIMIT_NPROC (Integer)
│ ├─RLIMIT_RSS (Integer)
│ ├─RLIMIT_RTPRIO (Integer)
│ ├─RLIMIT_RTTIME (Integer)
│ ├─RLIMIT_SIGPENDING (Integer)
│ ├─RLIMIT_STACK (Integer)
│ ├─RLIM_INFINITY (Integer)
│ ├─RLIM_SAVED_CUR (Integer)
│ ├─RLIM_SAVED_MAX (Integer)
│ ├─Status (Class)
│ ├─Sys (Module)
│ ├─Tms (Class)
│ ├─UID (Module)
│ ├─WNOHANG (Integer)
│ ├─WUNTRACED (Integer)
│ └─Waiter (Class)
├─Queue (Class)
├─RUBY_COPYRIGHT (String)
├─RUBY_DESCRIPTION (String)
├─RUBY_ENGINE (String)
├─RUBY_ENGINE_VERSION (String)
├─RUBY_PATCHLEVEL (Integer)
├─RUBY_PLATFORM (String)
├─RUBY_RELEASE_DATE (String)
├─RUBY_REVISION (Integer)
├─RUBY_VERSION (String)
├─Random (Class)
│ ├─DEFAULT (Random)
│ └─Formatter (Module)
├─Range (Class)
├─RangeError (Class)
├─Rational (Class)
├─RbConfig (Module)
│ ├─CONFIG (Hash)
│ ├─DESTDIR (String)
│ ├─MAKEFILE_CONFIG (Hash)
│ └─TOPDIR (String)
├─Regexp (Class)
│ ├─EXTENDED (Integer)
│ ├─FIXEDENCODING (Integer)
│ ├─IGNORECASE (Integer)
│ ├─MULTILINE (Integer)
│ └─NOENCODING (Integer)
├─RegexpError (Class)
├─RubyVM (Class)
│ ├─DEFAULT_PARAMS (Hash)
│ ├─INSTRUCTION_NAMES (Array)
│ ├─InstructionSequence (Class)
│ └─OPTS (Array)
├─RuntimeError (Class)
├─STDERR (IO)
├─STDIN (IO)
├─STDOUT (IO)
├─ScriptError (Class)
├─SecurityError (Class)
├─Signal (Module)
├─SignalException (Class)
├─SizedQueue (Class)
├─StandardError (Class)
├─StopIteration (Class)
├─String (Class)
├─StringIO (Class)
├─Struct (Class)
│ ├─Group (Class)
│ ├─Passwd (Class)
│ └─Tms (Class)
├─Symbol (Class)
├─SyntaxError (Class)
├─SystemCallError (Class)
├─SystemExit (Class)
├─SystemStackError (Class)
├─TOPLEVEL_BINDING (Binding)
├─TRUE (TrueClass)
├─Thread (Class)
│ ├─Backtrace (Class)
│ │ └─Location (Class)
│ ├─ConditionVariable (Class)
│ ├─Mutex (Class)
│ ├─Queue (Class)
│ └─SizedQueue (Class)
├─ThreadError (Class)
├─ThreadGroup (Class)
│ └─Default (ThreadGroup)
├─Time (Class)
│ ├─RFC2822_DAY_NAME (Array)
│ └─RFC2822_MONTH_NAME (Array)
├─TracePoint (Class)
├─TrueClass (Class)
├─TypeError (Class)
├─UnboundMethod (Class)
├─UncaughtThrowError (Class)
├─Warning (Module)
└─ZeroDivisionError (Class)
</pre>

## Constant Tree Printer

    def print_constants(nested_constants = [Object], nested_last_status = [], seen_constants = [])
      current_constant = nested_constants[-1]
      seen_constants << current_constant
      constants = current_constant.constants(false).select{|c| c.to_s =~ /^[A-Z]/ }.sort
      length = constants.length
      constants.each.with_index{ |constant_name, index|
        is_last = (index + 1) == length
        constant = current_constant.const_get(constant_name)
        print nested_last_status.map{ |is_hidden| is_hidden ? "  " : "│ " }.join
        print is_last ? "└─" : "├─"
        if seen_constants.include?(constant)
          puts '%{name} → %{alias}' % { name: constant_name, alias: constant.name }
        else
          puts '%{name} (%{class})' % { name: constant_name, class: constant.class }
          print_constants(nested_constants + [constant], nested_last_status + [is_last]) if constant.is_a? Module
        end
      }
    end

    puts "Object (Class)"
    print_constants

## Also See

- [New Ruby Startup](/43-new-ruby-startup.html)
- [Errors](/32-no-more-errors.html)