# 🏗️ Architecture Overview

## PipelineQuery → Initial LLM → TruthProbe → Score → [ADT if risky] → Safety Check → Final Response
## Components
1. **TruthProbe**: Regex + LLM Truth Analysis
2. **ADT**: 5 parallel critic roles
3. **Audit Trail**: Full transparency
4. **Safety Overrides**: Domain-specific blocks
