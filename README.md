# Character-Level Text Generation - RNN Comparison

### Project Overview
This project implements character-level recurrent neural networks for text generation, comparing stateless and stateful architectures with multiple recurrent layers. The models are trained on Fyodor Dostoyevsky's novel "The Idiot" as the reserved text corpus, exploring various generation strategies.

### Key Features
- Dual Architecture: Implementation of both stateless and stateful RNN variants
- Multi-Layer RNN: Experiments with stacked recurrent layers
- Training Corpus: Character-level training on Dostoyevsky's "The Idiot"

### Multiple Generation Strategies:
- Greedy decoding
- Temperature-based sampling
- Beam search implementation
- Character-Level Processing: Fine-grained text generation from character sequences

### Generation Methods
- Greedy Search: Deterministic selection of most probable next character
- Temperature Sampling: Controlled randomness in character selection
- Beam Search: Maintains multiple candidate sequences for improved coherence

### Technical Implementation
- Character-level tokenization and encoding of chosen text
- Stateful RNN with manual state management
- Stateless RNN with truncated backpropagation
- Custom beam search decoder
- Temperature-controlled sampling mechanisms

### Learning Outcomes
- Understanding of recurrent architectures for sequence generation
- Comparison of stateless vs stateful RNN behavior
- Practical implementation of advanced decoding strategies
- Text generation quality analysis across different methods on classic literature
