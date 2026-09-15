# Urdu Question Generation using LSTM & Luong Attention

An end-to-end **Urdu Question Generation** system built from scratch using a sequence-to-sequence RNN architecture. The system takes an Urdu sentence containing a marked answer span and generates a question for which the marked span should be the answer.

## 🚀 Project Overview

This project implements an Urdu Question Generation pipeline using a **2-layer Bidirectional LSTM Encoder, Luong General Attention, and a 2-layer LSTM Decoder**.

A custom **SentencePiece Unigram tokenizer** with an 8,000-token vocabulary is used to convert Urdu text into subword token IDs.


پاکستان کا دارالحکومت <ans>اسلام آباد</ans> ہے۔
