# Financial Due Diligence (FDD) LTM EBITDA & NWC Model

This repository contains an Excel-based Financial Due Diligence (FDD) mini-case simulating a buy-side M&A transaction. The model converts raw target data into LTM (Last Twelve Months) Adjusted EBITDA, establishes a normalized working capital (NWC) peg, and derives net debt to bridge enterprise value to implied equity value.

## Key Technical Highlights

The model demonstrates the precise execution of critical FDD mechanics. I established a true run-rate for the business by executing a normalization schedule that adds back a one-time 150 legal settlement and normalizes a 50 favorable operational variance, along with a 30 year-end timing adjustment. To protect the buyer's balance sheet at close, the model calculates a historical average Normalized Working Capital (NWC) peg. Furthermore, the net debt build extracts 50 in restricted cash to present an airtight view of the actual debt burden the buyer will assume.

## Deal Insights

Analysis indicates a material working capital build in Q4, with closing NWC of 420 against a normalized peg of 324. This ~100 variance suggests potential cash retention or operational buildup prior to close. If not normalized, this would require a purchase price adjustment, directly impacting deal value.
