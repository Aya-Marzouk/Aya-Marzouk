"use client";

import { motion } from "framer-motion";
import { ArrowRight } from "lucide-react";

export default function Home() {
  return (
    <main className="relative min-h-screen overflow-hidden bg-[#050816] text-white">

      {/* Animated Background */}
      <div className="absolute inset-0">

        <div className="absolute -left-40 top-20 h-96 w-96 rounded-full bg-cyan-500/20 blur-[120px]" />

        <div className="absolute right-0 bottom-0 h-96 w-96 rounded-full bg-violet-600/20 blur-[140px]" />

        <div className="absolute left-1/2 top-1/3 h-72 w-72 rounded-full bg-sky-500/10 blur-[100px]" />

      </div>

      {/* Grid */}
      <div className="absolute inset-0 opacity-[0.05] bg-[linear-gradient(#ffffff_1px,transparent_1px),linear-gradient(to_right,#ffffff_1px,transparent_1px)] bg-[size:60px_60px]" />

      <section className="relative z-10 flex min-h-screen items-center justify-center px-6">

        <div className="max-w-6xl">

          <motion.p
            initial={{ opacity: 0, y: 40 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: .8 }}
            className="mb-6 text-cyan-400 text-xl font-medium"
          >
            👋 Welcome to my portfolio
          </motion.p>

          <motion.h1
            initial={{ opacity: 0, y: 60 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 1 }}
            className="text-7xl md:text-8xl font-black leading-none"
          >
            Aya
            <br />

            <span className="bg-gradient-to-r from-cyan-400 via-sky-400 to-violet-500 bg-clip-text text-transparent">
              Ibrahim
            </span>

          </motion.h1>

          <motion.h2
            initial={{ opacity: 0 }}
            animate={{ opacity: 1 }}
            transition={{ delay: .7 }}
            className="mt-8 text-3xl font-semibold text-zinc-300"
          >
            Data Analyst • Business Analyst
          </motion.h2>

          <motion.p
            initial={{ opacity: 0 }}
            animate={{ opacity: 1 }}
            transition={{ delay: 1 }}
            className="mt-8 max-w-2xl text-xl leading-9 text-zinc-400"
          >
            Turning raw data into interactive dashboards and meaningful
            business insights using Power BI, SQL Server, Tableau,
            Data Modeling, Airflow, and modern analytics.
          </motion.p>

          <motion.div
            initial={{ opacity: 0, y: 40 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ delay: 1.3 }}
            className="mt-12 flex gap-5"
          >

            <button className="rounded-full bg-cyan-400 px-8 py-4 font-semibold text-black transition hover:scale-105">
              View Projects
            </button>

            <button className="group flex items-center gap-2 rounded-full border border-cyan-400/40 px-8 py-4 transition hover:border-cyan-400">

              Contact Me

              <ArrowRight
                className="transition group-hover:translate-x-1"
                size={18}
              />

            </button>

          </motion.div>

        </div>

      </section>

    </main>
  );
}
