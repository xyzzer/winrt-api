---
-api-id: P:Windows.Media.Core.TimedMetadataTrackError.ErrorCode
-api-type: winrt property
---

<!-- Property syntax
public Windows.Media.Core.TimedMetadataTrackErrorCode ErrorCode { get; }
-->

# Windows.Media.Core.TimedMetadataTrackError.ErrorCode

## -description
Gets the error code associated with the timed metadata track error.

## -property-value
The error code associated with the timed metadata track error.

## -remarks
This value provides high-level information about the error that occurred with the timed metadata track. To get the low-level exception associated with the error, call [TimedMetadataTrackError.Propagate](timedmetadatatrackerror_propagate.md) which will cause the underlying exception to be raised.

## -examples

## -see-also
[TimedMetadataTrackError::Propagate](timedmetadatatrackerror_propagate.md)