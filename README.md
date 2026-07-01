"use client";

import { motion } from "framer-motion";
import { ArrowRight } from "lucide-react";

export default function Home() {
  return (
    <main className="relative min-h-screen overflow-hidden bg-[#050816] text-white">

      {/* Aurora Background */}
      <div className="absolute inset-0 -z-10">

        <div className="absolute left-[-150px] top-[-100px] h-[450px] w-[450px] rounded-full bg-fuchsia-600/20 blur-[140px] animate-pulse" />

        <div className="absolute right-[-150px] bottom-[-120px] h-[450px] w-[450px] rounded-full bg-cyan-500/20 blur-[140px] animate-pulse" />

        <div className="absolute left-1/2 top-1/3 h-[350px] w-[350px] -translate-x-1/2 rounded-full bg-violet-500/10 blur-[120px]" />

      </div>

      {/* Grid */}
      <div className="absolute inset-0 opacity-5 bg-[linear-gradient(#ffffff_1px,transparent_1px),linear-gradient(to_right,#ffffff_1px,transparent_1px)] bg-[size:60px_60px]" />

      <section className="mx-auto flex min-h-screen max-w-7xl items-center px-8">

        <div>

          <motion.p
            initial={{ opacity: 0, y: 25 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: .6 }}
            className="mb-6 text-lg tracking-[0.3em] uppercase text-cyan-400"
          >
            Welcome To My Portfolio
          </motion.p>

          <motion.h1
            initial={{ opacity: 0, y: 40 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: .8 }}
            className="text-6xl font-black leading-none sm:text-7xl lg:text-8xl"
          >

            Aya

            <br />

            <span className="bg-gradient-to-r from-fuchsia-500 via-violet-400 to-cyan-400 bg-clip-text text-transparent">
              Ibrahim
            </span>

          </motion.h1>

          <motion.h2
            initial={{ opacity: 0 }}
            animate={{ opacity: 1 }}
            transition={{ delay: .5 }}
            className="mt-8 text-2xl font-semibold text-zinc-300"
          >

            Data Analyst • Business Analyst

          </motion.h2>

          <motion.p
            initial={{ opacity: 0 }}
            animate={{ opacity: 1 }}
            transition={{ delay: .8 }}
            className="mt-8 max-w-2xl text-lg leading-8 text-zinc-400"
          >
            Passionate about transforming raw data into meaningful insights
            through Power BI, SQL Server, Tableau, Data Modeling,
            Apache Airflow, and interactive dashboards.
          </motion.p>

          <motion.div
            initial={{ opacity: 0, y: 30 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ delay: 1 }}
            className="mt-12 flex flex-wrap gap-5"
          >

            <button className="rounded-full bg-gradient-to-r from-fuchsia-600 to-cyan-500 px-8 py-4 font-semibold shadow-lg shadow-cyan-500/20 transition-all duration-300 hover:scale-105 hover:shadow-cyan-400/40">

              View Projects

            </button>

            <button className="group flex items-center gap-2 rounded-full border border-cyan-400/40 px-8 py-4 transition-all hover:border-cyan-400 hover:bg-white/5">

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
